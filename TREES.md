# Trees
## What are Trees?
Yes, we all know or should know the trees that grow in nature and provide us with beautiful sceneary and decorate our lawns with wonderful autumn colors but those are not the trees we are talking about today. We are discussing the data structure trees! Trees are similar to our last data structure we studied, Linked List. Imagine a linked list but each node could connect to more than one node down the line. So instead of a NEXT they have multiple nodes they point to. This can also be said that each parent node has multiple children nodes. 

## Binary
A binary tree is a tree that each element or parent node has at most two children nodes. Since there are at most two children nodes, we use the term left and right. So you can think of it like a linked list but instead of NEXT we have LEFT and RIGHT. 

## Binary Search Trees
Binary search trees are great! The reason we like a binary search tree is because searching through a binary search tree is really fast because the data is organized as it is entered into the tree. Elements are compred to a node and if they are greater in value they will move to the right child spot of the node. If there is another element in that spot already then the new element is compare to that one to see if it will move down to the child left or right spot. This continues until a spot is found that is empty. This means the children to the left of an element will always be less and the right will always be greater. This allows our search time to be cut in half because we instantly cut half of our tree out of the equation. 

## Balanced VS Unbalanced
Like Thanos said in Avengers, perfectly balanced, as all things should be. We like balanced trees because they are easy on the eyes and we aren't wasting space. A balanced tree is one that has the same or close to the same amount of elements or data on one side of the tree as the other side of the tree. Below you have two examples, one of a balance tree and the other of an unbalanced tree

## Implementing Trees

### Common Terms and Operations
| Common Linked List Terms and Operations  | What does it do? | How to write it in Python | Big O Timing |
| ------------- | ------------- | ------------- | ------------- |
| insert(value) | Adds data into the tree | my_deque.appendleft(value) | O(log n) |
| insert_tail(value)  | Adds data after the tail  | my_deque.append(value) | O(1) |
| insert(i, value)  | Adds data after node "i"  | my_deque.insert(i, value) | O(n), the reason this is O(n) is because it has to loop through the linked list|
| remove_head()  | Removes the head | value = my_deque.popleft() | O(1)|
| remove_tail(index)  | Removes the tail | value = my_deque.pop() | O(1)|
| remove(i)  | Removes node "i" | del my_deque[i] | O(n), again the reason this is O(n) is because it has to loop through the linked list |
| size()  | Return size of the linked list  | length = len(my_deque) | O(1)|
| empty()  | Returns true if the length of the linde list is zero. | if len(my_deque) == 0: | O(1)|

### Problem 1
https://qvault.io/python/binary-search-tree-in-python/
### Problem 2

## Why use Trees?
