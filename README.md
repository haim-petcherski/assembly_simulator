# assembly_simulator

Implementing a system composed of processor simulator and an assembler in C for a given invented assembly language.
This system also includes simulting of disc memory, registers, interrupts and a clock.
the following image shows the scheme of the system that was implemented in the project:
![](https://github.com/haim-petcherski/Processor-simulator-for-Assembly/blob/main/%E2%80%8F%E2%80%8Fsystem%20scheme.PNG)

As you can see the tests for the system that were written in Assembly enter into the assembler. Then the output of the assembler, memin.txt is a translation of the Assembly code into Hexa base, enters into the processor. Afterwards the processor creates output that includes the result of the mission in the test and statistic information about the processing of the test. for example: the final values in the registers, final contents in disc, the number of cycle of the last update in each register, etc.
