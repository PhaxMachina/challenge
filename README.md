# challenge
uncover the VM bytecode (devirtualizeMe, I guess) + capture the flag

# Archival notice

this is a failure, and i am scrapping the project as a result.
you can still do every part of the challenge except devirtualization, since the compiler had generated an optimized path that the original input used.
bye

# Notes

- The challenge binary is located in this repository, named `challenge.bin`
- Your input "key" to the binary as an argument, must be 16 characters in length (a-z, A-Z ... no numbers or special symbols included here) ... If your input isn't exactly 16 characters, the program will crash, and that is not what any of us want.
- Recover the VM bytecode, the flag, and craft an input to the binary that results in the flag being displayed (no tricks) ... DM all of those to me on discord `@terraphax` ...
- For the VM bytecode, send a screenshot or inline text of your disassembled basic blocks of the custom instruction set... for the flag, send the string ... for the correct input, send the string ...

# Hint

As a hint, the function that has parts of it virtualized is at 0x0000000140001770 during runtime. 
Also, the binary is a PE32+, or PE64 binary, for Windows. 
