# Big O Notation
## What is Big O Notation?
Imagine you are working to build software for Tesla's new self driving cars. You create an AI for the car and it works! The only down side is that when your software is running, it takes several seconds for the AI to make the next decision. Now that is an issue. In many siutations when driving, a second of a difference can make all the difference between a close call and a wreck. As developers we want programs that execute fast. Now most programs will run very fast given very little data. It is when we are given a lot of data that the time to execute can increase dramatically. 
Ideally a great code would run the same speed or close to the same speed with any amount of data added to it. This would be O(1) notation. Many times we settle with having a program that increases the same amount you increase the data by. This is O(logn) notation. We always want to shoot for the O(1) or O(n). (These are read as O of 1 or O of n.)

## A Look at a Big O Notation Graph
![Big Oh Notation Chart](bigochart.gif)

## Calculating Big O Notation
### Some Basic Rules
1) Conditional checks are constant (i.e. O(1)).
2) Constants are dropped.
3) Nested loops are multiplied together.
4) Sequential loops are added.
5) Only the largest term is kept, all others are dropped.
6) Go one line at a time

### A Break Down of the main Big O Sections

#### O(1)
What is O(1). O(1) is constant time. The time is consistent for each execution. Imagine if you work at an amusement park. It takes the rollercoaster exactly 3 minutes to complete the track, and then that ride or particular task is considered to be complete. It doesn’t matter if you only send one ride through the track that day, or a hundred rides that day, you have sent the rides in a consistent amount of time.

So as per our example earlier, we don’t care about O(1), O(2), etc. We round it down to O(1) which is to say that our operation is a flat line in terms of scalability. It will take the same amount of time. This is predictable and very scalable. See an example:
``` python:
def constant_algo(items):
    result = items[0] * items[0]
    print ()

constant_algo([4, 5, 6, 8])
```

#### O(n)

#### O(n^2)





