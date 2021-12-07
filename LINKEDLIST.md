# Linked List
## What are linked lists? 
Linked List can be intimidating but don't you worry! They can actually be lots of fun! A major characteristic of linked lists is that they are linear data structures. This means that there is a sequence and an order to how they can be traversed and constructed.
![Linked List Example](LinkedList.PNG)
## Doubly Linked Lists
![Doubly Linked List Example](DoublyLinkedList.PNG)

## How to Implement
### Inserting 
#### Inserting From the Head
To Insert at the head we need to:
1) Create our new node (new_node)
2) Set the NEXT of the new node to the current head (new_node.next = self.head)
3) Set PREV of current head to the new node (self.head.prev = new_node)
4) Set the head equal to the new node (self.head = new_node)
![Inserting at the head Example](InsertHeadLL.PNG)

#### Inserting in the Middle
To Insert in the middle of our Linked List we need to:
1) Create our new node (new_node)
2) Set PREV of the new node to the current node (new_node.prev = current)
3) Set NEXT of new node to the next node after the current (new_node.next = current.next)
4) Set PREV of next mode after current node to the new node, establishing this connection will automatically delete the previous connection (current.next.prev = new_node)
5) Set NEXT of current node to new node (current.next = new_node)
![Inserting in the middle Example](InsertMidLL.PNG)

#### Inserting From the Tail
To Insert at the tail we need to:
1) Create our new node (new_node)
2) Set PREV of the new node to the current tail (new_node.prev = self.tail)
3) Set NEXT of current tail to the new node (self.tail.next = new_node)
4) Set the tail equal to the new node (self.tail = new_node)
![Inserting at the tail Example](InsertTailLL.PNG)

### Deleting 
#### Deleting From the Head
![Deleting at the head Example](RemoveHeadLL.PNG)
#### Deleting in the Middle
![Deleting in the middle Example](DeleteMidLL.PNG)
#### Deleting From the Tail
![Deleting at the tail Example](RemoveTailLL.PNG)
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




## Performance of Linked Lists

### Problem 1
### Solution 1
## Try it on your own!
Creating your own linked list https://realpython.com/linked-lists-python/#implementing-your-own-linked-list
