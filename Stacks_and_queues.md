# Stacks and queues:-

Stacks and queues are fundamental data structures used in computer science and programming. They both represent collections of elements, but they differ in how elements are accessed and removed.

## Stack:

- **Definition:** A stack is a Last-In-First-Out (LIFO) data structure. It behaves like a stack of objects, where the last item added is the first one to be removed.
- **How it works:** Imagine a stack of books. You can add a new book on top, and when you want to remove a book, you can only take the one from the top. This principle applies to a stack data structure as well.
- **Operations:**
1. Push: Adds an element to the top of the stack.
2. Pop: Removes and returns the top element from the stack.
3. Peek: Returns the top element without removing it.
- **Example:** Let's say you have a stack of integers [3, 7, 1]. If you push the value 5, the stack becomes [3, 7, 1, 5]. If you pop an element, you get 5 and the stack becomes [3, 7, 1].


## Queue:

- **Definition:** A queue is a First-In-First-Out (FIFO) data structure. It resembles a line of people waiting for something, where the first person who joins the line is the first one to be served.
- **How it works:** Just like in a real-life queue, new elements are added to the end, and removal happens from the front of the queue.
- **Operations:**
1. Enqueue: Adds an element to the end of the queue.
2. Dequeue: Removes and returns the front element from the queue.
3. Peek: Returns the front element without removing it.
- **Example:** Let's consider a queue of characters ['1', '2', '3']. If you enqueue the value '4', the queue becomes ['1', '2', '3', '4']. If you dequeue an element, you get '1', and the queue becomes ['2', '3', '4'].

## summary:

Stacks and queues have different access and removal behaviors.
Stacks follow the LIFO principle, while queues follow the FIFO principle.
Both stacks and queues can be implemented using various programming languages, and they have important applications in solving problems and designing algorithms.
