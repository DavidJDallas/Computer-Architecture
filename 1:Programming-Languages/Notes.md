# Programming Languages

(1) High level languages: C, Python, JS, etc
(2) Machine Language: The actual binary commands executed by a microarchitecture
(3) Assembly language (AL): An intermediate langauge that is human readable but very closely tied to machine language commands. 

HLLs are translated into machine langauge using a toolchain. This is typicalyl referred to as compiling the programme.  

Some HLLs are not compiled but are instead loaded into an interpretor. Often referred to as a script language or scripts. The interpreter is a compiled programme that reads in a script and executes the commands contained in the script. 

There's an almost 1-1 correspondence between assembly languages and machine language commands. Assembly language is most commonly an intermediate product of the tool chain when converting an HLL to ML. But it's sometimes still written by hand. 

ML commands are binary instructions read from memoryand passed along a bus to the processor for execution. 
Architectures are often divided into 2 groups:
(a) Complex Instruction Set Computer (CISC)
(b) Reduced Instruction SEt Computer (RISC)

RISC architecture tends to use a fixed length for all ML commands. ARM uses 32 bit instructions and AVR uses 16 or 32 bit instructions.

CISC ML instructions are variable length. An ML command contains two types of information 
- The type of instruction being executed (the opcode/funct fields)
- The arguments or operands of the instruction.

The ML commands are ultimately placed in some type of executable file.

## Toolchain stages

(1) Preprocessor

In C and C++, this step translates C/C++ into C/C++.

(2) Compiler

Converts C into assembly language. Most compilers will automatically delete this file in the process. 

(3) Assembler

Converts AL into ML instructions that are stored in an object file. Components of an object file:
- Text segment: Contains the ML instructions of the programme.
- Data segment: The values of all initialized variables stored in data memory
- Relocation Information/Symbol Table: Contains information to help resolve addresses during linking.  

(4) Linker

Linking is the final stage and is what makes it possible to use programming libraries. After the assembler the object file that gets produced by the assembler is not yet a runnable programme. The linker creates the runnable programme by combining the ML object file with one or more libraries. The result is stored in an executable or binary file.  

Linking can be done in two different ways:
(i) Static Linking

All ML code from a particular library is copied into the executable. Used by simple micro-controllers. 

(ii) Dynamic linking. 