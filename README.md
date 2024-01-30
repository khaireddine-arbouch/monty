# 0x19. C - Stacks, Queues - LIFO, FIFO

## Project Overview

You've just entered the advanced stage of the Monty project! This project involves implementing various operations on stacks and queues in the Monty language, a scripting language compiled into Monty bytecode files. The primary goal is to create an interpreter for Monty ByteCodes, focusing on stack and queue manipulations.

## Tasks

### 0. push, pall

#### Implement the push opcode

- **Usage:** `push <int>`
- Pushes an element to the stack.
- Error handling: If `<int>` is not an integer or if no argument is given, print an error message and exit with `EXIT_FAILURE`.

#### Implement the pall opcode

- **Usage:** `pall`
- Prints all values on the stack, starting from the top.

### 1. pint

#### Implement the pint opcode

- **Usage:** `pint`
- Prints the value at the top of the stack, followed by a new line.
- Error handling: If the stack is empty, print an error message and exit with `EXIT_FAILURE`.

### 2. pop

#### Implement the pop opcode

- **Usage:** `pop`
- Removes the top element of the stack.
- Error handling: If the stack is empty, print an error message and exit with `EXIT_FAILURE`.

### 3. swap

#### Implement the swap opcode

- **Usage:** `swap`
- Swaps the top two elements of the stack.
- Error handling: If the stack contains less than two elements, print an error message and exit with `EXIT_FAILURE`.

### 4. add

#### Implement the add opcode

- **Usage:** `add`
- Adds the top two elements of the stack.
- Error handling: If the stack contains less than two elements, print an error message and exit with `EXIT_FAILURE`.

### 5. nop

#### Implement the nop opcode

- **Usage:** `nop`
- Does nothing.

### 6. sub

#### Implement the sub opcode

- **Usage:** `sub`
- Subtracts the top element of the stack from the second top element.
- Error handling: If the stack contains less than two elements, print an error message and exit with `EXIT_FAILURE`.

### 7. div

#### Implement the div opcode

- **Usage:** `div`
- Divides the second top element of the stack by the top element.
- Error handling: If the stack contains less than two elements or if the top element is 0, print an error message and exit with `EXIT_FAILURE`.

### 8. mul

#### Implement the mul opcode

- **Usage:** `mul`
- Multiplies the second top element of the stack with the top element.
- Error handling: If the stack contains less than two elements, print an error message and exit with `EXIT_FAILURE`.

### 9. mod

#### Implement the mod opcode

- **Usage:** `mod`
- Computes the remainder of the division of the second top element by the top element.
- Error handling: If the stack contains less than two elements or if the top element is 0, print an error message and exit with `EXIT_FAILURE`.

### 10. comments

#### Implement handling for comments

- When the first non-space character of a line is `#`, treat the line as a comment (do nothing).

### 11. pchar

#### Implement the pchar opcode

- **Usage:** `pchar`
- Prints the char at the top of the stack, treating the integer as the ASCII value.
- Error handling: If the stack is empty or the value is out of the ASCII range, print an error message and exit with `EXIT_FAILURE`.

### 12. pstr

#### Implement the pstr opcode

- **Usage:** `pstr`
- Prints the string starting at the top of the stack, considering each integer as the ASCII value.
- Stops printing when the stack is over, the value is 0, or the value is out of the ASCII range.

### 13. rotl

#### Implement the rotl opcode

- **Usage:** `rotl`
- Rotates the stack to the top.
- The top element becomes the last one, and the second top element becomes the first one.

### 14. rotr

#### Implement the rotr opcode

- **Usage:** `rotr`
- Rotates the stack to the bottom.
- The last element becomes the top element.

### 15. stack, queue

#### Implement the stack and queue opcodes

- **stack opcode Usage:** `stack`
- Sets the data format to stack (LIFO).
- **queue opcode Usage:** `queue`
- Sets the data format to queue (FIFO).
- When switching mode, the top of the stack becomes the front of the queue, and vice versa.

### 16. Brainf*ck

#### Write a Brainf*ck script

- Create a Brainf*ck script that prints "School" followed by a new line.
- Store Brainf*ck files inside the `bf` subdirectory.

### 17. Add two digits

#### Add two digits given by the user

- Read two digits from stdin, add them, and print the result.
- The total will be one digit-long (<10).

### 18. Multiplication

#### Multiply two digits given by the user

- Read two digits from stdin, multiply them, and print the result.
- The result of the multiplication will be one digit-long (<10).

### 19. Multiplication level up

#### Multiply two digits given by the user

- Read two digits from stdin, multiply them, and print the result followed by a new line.

## Copyright

Copyright © 2024 ALX. All rights reserved.
