# Let's learn Queue Data Structures!
Imagine you are waiting in line for your favorite Fast Food! You are the second one in line. Right after you walked in, five other customers walked in and are in line behind you. The staff start helping people in the very back of the line first! This would make you very upset, right? This is why we have queues! They follow the First In First Out (FIFO) mentatlity. 

In programming they are a container that will keep track of the order data is added to the container. This allows us to build the queue and manipulate the queue.

## Sample Problem #1
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

# 'Jared' and 'Jessica' remain
print(customers) 
```

## Sample Problem #2

```python
input_queue = Queue()

# The player wants to get the upper hand so pressing the right combination of buttons quickly
input_queue.enqueue('DOWN')
input_queue.enqueue('RIGHT')
input_queue.enqueue('B')

# Now we can process each item in the queue by dequeueing them
key_pressed = input_queue.dequeue() # 'DOWN'

# We'll probably change our player position
key_pressed = input_queue.dequeue() # 'RIGHT'

# We'll change the player's position again and keep track of a potential special move to perform
key_pressed = input_queue.dequeue() # 'B'

# This can do the act, but the game's logic will know to do the special move
```
