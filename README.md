0x19. C - Stacks, Queues - LIFO, FIFO.
OBJECTIVE: To create an interpreter for Monty ByteCodes files.
Monty 0.98 is a scripting language that is first compiled into Monty byte codes.
It relies on a unique stack, with specific instructions to manipulate it.
Files containing Monty byte codes usually have the .m extension.
Monty byte code files can contain blank lines (empty or made of spaces only, and any additional text after the opcode or its required argument is not taken into account.

OPCODES:
push adds an element to the stack.
pall prints all the values on the stack, starting from the top of the stack.
pint prints the value at the top of the stack, followed by a new line.
pop removes the top element of the stack.
swap swaps the top two elements of the stack.
add adds the top two elements of the stack.
