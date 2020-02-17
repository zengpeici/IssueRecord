1.
	*Q:What is a queue?
	A:Queue is a first in, first out data structure. There are two types of block and unblock.
2.
	*Q:What is blocking queue?
	A:Blocking queue is a queue that blocks when you try to dequeue from it and the queue is empty, or if you try to enqueue items to it and the queue is already full. A thread trying to dequeue from an empty queue is blocked until some other thread inserts an item into the queue. A thread trying to enqueue from a full queue is blocked until some other thread make space int the queue.