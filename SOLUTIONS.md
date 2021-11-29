# Queue Problem 2 Solution

```python
input_queue = Queue()

# The player wants to get the upper hand so pressing the right combination of buttons quickly
input_queue.append('DOWN')
input_queue.append('RIGHT')
input_queue.append('B')

# Now we can process each item in the queue by dequeueing them
key_pressed = input_queue.pop() # 'DOWN'

# We'll probably change our player position
key_pressed = input_queue.pop() # 'RIGHT'

# We'll change the player's position again and keep track of a potential special move to perform
key_pressed = input_queue.pop() # 'B'

# This can do the act, but the game's logic will know to do the special move
```
