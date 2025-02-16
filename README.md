# Queue-Implementation-using-Linked-List-in-C
This project implements a Queue using a singly linked list in C
The queue follows the FIFO (First In, First Out) principle, allowing users to perform operations such as enqueue, dequeue, and display.

Features
This program provides the following queue operations:

Enqueue – Insert an element into the queue.
Dequeue – Remove the front element from the queue.
Display – Show all elements in the queue.
Exit – Terminate the program.
Functions and Their Purpose
Function	Description
enqueue()	Inserts an element at the rear of the queue.
dequeue()	Removes and returns the front element.
display()	Prints all elements in the queue.
Edge Cases Handled
Queue Overflow: If memory allocation fails, a warning is displayed.
Queue Underflow: If a dequeue operation is performed on an empty queue, an error message is shown.
Possible Enhancements
Implement a circular queue to optimize space usage.
Add a size function to return the number of elements in the queue.
Implement a priority queue for better task management.
