Push and Pop
Let's use arrays to implement a Stack. We create an array with a max size which decides the max capacity of our stack. To trace the top element of stack we create a variable top which hold the position of array where the top element is present. Initially the top variable will be -1.

Push Operation:
The push operation adds an element to the top of the stack. Here's a step-by-step explanation of the push operation:

You have an element that you want to store in the stack.
You check if the stack is full. If the stack has a maximum size and it is already full, this is usually called a stack overflow, and the element cannot be added.
If the stack is not full, you place the element at the top of the stack.
You update the pointer that always points to the top of the stack (often referred to as "top" in programming). After the push, "top" will be pointing to the newly added element.

Pop Operation:
The pop operation removes the top element from the stack. Here's how the pop operation works:

First, you check if the stack is empty. If it's empty, there is nothing to pop, and this condition is known as a stack underflow.
If the stack is not empty, you proceed to remove the element that "top" is currently pointing to.
After removing the element, you update the "top" pointer to point to the new top element of the stack, which is the previous element before the one you just popped.
The popped element is returned or kept for further processing, depending on the implementation and usage.
It’s important to note that with the pop operation, you're typically not physically removing the element from the memory; you're just logically considering it removed by moving the "top" pointer.

Reference: CodeChef
