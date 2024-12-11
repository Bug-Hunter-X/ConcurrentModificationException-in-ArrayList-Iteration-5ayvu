# ConcurrentModificationException in Java
This example demonstrates a common error in Java: the ConcurrentModificationException. This exception occurs when an attempt is made to modify a collection (like ArrayList) while iterating over it using an iterator or enhanced for loop (for-each).

The provided code attempts to remove an element from an ArrayList during iteration, leading to the exception. The solution shows a safer way to remove elements using an Iterator and its `remove()` method, or by iterating in reverse order.