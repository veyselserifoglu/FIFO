# FIFO


*Pop Operation Functional algorithm:*
- Functional sequence description:
    1. RE signal (or Pop signal) transitions to HIGH from LOW.
    2. The entry in the memory cell addressed by the current counter / stack pointer value is read into the output register.
    3. If the stack pointer value is exactly 0, the stack pointer value remains unchanged, and the empty flag is set to HIGH. 
    4. If the condition in step "3" is not met, the current value of the stack pointer is decremented by 1.

*Reset Operation Functional algorithm:*
- Functional sequence description:
    1. Reset signal transitions to HIGH from LOW.
    2. The stack pointer is set to its initial value (typically 0).
    3. The full flag is set to LOW.
    4. The empty flag is set to HIGH. 