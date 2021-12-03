# Linked List
## What are linked lists? 
Linked List can be intimidating but don't you worry! They can actually be lots of fun! A major characteristic of linked lists is that they are linear data structures. This means that there is a sequence and an order to how they can be traversed and constructed.

| Common Linked List Terms and Operations  | What does it do? | How to write it in Python | Big O Timing |
| ------------- | ------------- | ------------- | ------------- |
| insert_head(value)  | Adds data before the head  | my_deque.appendleft(value) | O(1)|
| insert_tail(value)  | Adds data after the tail  | my_deque.append(value) | O(1) |
| insert(i, value)  | Adds data after node "i"  | my_deque.insert(i, value) | O(n), the reason this is O(n) is because it has to loop through the linked list|
| remove_head()  | Removes the head | value = my_deque.popleft() | O(1)|
| remove_tail(index)  | Removes the tail | value = my_deque.pop() | O(1)|
| remove(i)  | Removes node "i" | del my_deque[i] | O(n), again the reason this is O(n) is because it has to loop through the linked list |
| size()  | Return size of the linked list  | length = len(my_deque) | O(1)|
| empty()  | Returns true if the length of the linde list is zero. | if len(my_deque) == 0: | O(1)|



## Doubly Linked Lists
## Performance of Linked Lists
## How to Implement
### Problem 1
### Solution 1
## Try it on your own!
Creating your own linked list https://realpython.com/linked-lists-python/#implementing-your-own-linked-list
