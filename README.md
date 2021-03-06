# dbcpuEmulator
**Description**
  - [dcpu](https://github.com/dma-neves/dbcpu) emulator written in c. 
  - The emulator only runs [assembled](https://github.com/dma-neves/dcpuAssembler) programs and prints the state of the cpu (registers, stack, etc).

**Usage**
  - Compile the program using the given makefile.
  - The emulator can be ran in two modes: e - executes the whole program ands shows the final state; s - executes one step/instruction at a time showing the cpu's state after each step.
  - Note: When the emulation is ran in the 'e' mode, if a break instruction is fetched, the emulator will print the state of the cpu and await for user input to continue.
