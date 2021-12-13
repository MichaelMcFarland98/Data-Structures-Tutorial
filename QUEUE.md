# Let's learn Queue Data Structures!
Imagine you are waiting in line for your favorite Fast Food! You are the second one in line. Right after you walked in, five other customers walked in and are in line behind you. The staff start helping people in the very back of the line first! This would make you very upset, right? This is why we have queues! They follow the First In First Out (FIFO) mentatlity. 

In programming they are a container that will keep track of the order data is added to the container. This allows us to build the queue and manipulate the queue. If it is easier, just imgagine the data is in a line and you are telling it what to do! Let's take a look at some common terms and how to implement them into our python code.

| Common Queue Term  | What does it do? | How to write it in Python | Big O Timing |
| ------------- | ------------- | ------------- | ------------- |
| enqueue(value)  | Adds the data to the back of the queue  | my_queue.append(value) | O(1)|
| dequeue()  | You can either remove and return the item from the front of the queue; or pop off index 0  | value = my_queue[0]  <br/> del my_queue[0] <br/> or <br/>value = my_queue.pop(0) | O(n) |
| size()  | Return size of the queue  | length = len(my_queue) | O(1)|
| empty()  | Returns true if the length of the queue is zero. | if len(my_queue) == 0: | O(1)|

Lets look at the sample problem #1 below. We have a queue of people entering your boba shop, they are all lining up and making their orders! You want to make their orders in the order you received them. Help finish the code below to create a program to keep track of that for you!

## Sample Problem #1
```python
customers = []

# Let's enqueue or add some customers into our list (Add: Dave, Sara, Jared, and Jessica in this order)
  #Add your code here
print(customers) #We should get Dave, Sara, Jared, Jessica

# Now let's dequeue or take our our first customer, we should get 'Dave'
  #Add your code here
print(first_item)

# If we dequeue again we'll get the next customer in line 'Sara'
first_item = customers.pop(0)
print(first_item)

#Let's check the size of our line to know how busy we are right now!
  #Add code

#Our last customers are...
print(customers) 
```

## Solution to Problem #1
```python
customers = []

# Let's enqueue some customers into our list
customers.append('Dave')
customers.append('Sara')
customers.append('Jared')
customers.append('Jessica')

# Now let's dequeue our first customer, we should get 'Dave'
first_item = customers.pop(0)
print(first_item)

# If we dequeue again we'll get the next customer in line 'Sara'
first_item = customers.pop(0)
print(first_item)

#Let's check the size of our line to know how busy we are right now!
length = len(customers)

#Our last customers are...
print(customers) 
```
Now let's look at another example! Again we are needing a queue for our Boba shop! The code before was very simple and not ideal for using in a company because we would have to add every line of code. More often we will be creating a program we can run and using functions to add and remove data from the queue. The link below will take you to replit.com which is an online repel. You can run and see the file of the code there. If you are going to work on the code yourself you will need to copy the file and paste it into your editor or create an account on replit.com and fork the repel on the link below. I have also provided a solution to reference if you get stuck. 


### [Sample Problem #2](https://replit.com/@MichaelMcFarla5/QueueLessonProblem#main.py)
 [See Solution](https://replit.com/@MichaelMcFarla5/QueueLessonSolution#main.py)
 
 Go back to our main page? [Click Here](README.md)
