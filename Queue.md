# Deque:
- Deque supports both stack and queue operations, it can be used as both.
- Double ended queues are sequence containers with the feature of expansion and contraction on both the ends.
- The Deque data structure supports clockwise and anticlockwise rotations in O(1) time which can be useful in certain applications.

### Operations:
- push_front(): Adds an item at the front of Deque.
- push_back(): Adds an item at the rear of Deque.
- pop_front(): Deletes an item from front of Deque.
- pop_back(): Deletes an item from rear of Deque
######

- front(): Gets the front item from queue.
- back(): Gets the last item from queue.
- isEmpty(): Checks whether Deque is empty or not.
- isFull(): Checks whether Deque is full or not.
- size() : gives size

### Application:
the problems where elements need to be removed and or added both ends can be efficiently solved using Deque. For example:
- Maximum of all subarrays of size k problem.
    - Sliding Window Syntax based
- 0-1 BFS 
- Find the first circular tour that visits all petrol pumps.
