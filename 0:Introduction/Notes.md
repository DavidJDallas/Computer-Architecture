# Introduction

Course aims to bridge the gap between logic gates and writing code in terms of conceptual understanding. 

## Micro-Architecture

MA executes a series of low-level machine language instructions. 
MA is the specific arrangement of registers, ALUs, finite machines, memories, and other logic building blocks needed to implement an architecture. 

The MA can be split into various parts. The processor is like the brain and is where the calculations are performed. We also have a memory. Information flows between the two, and this connection and flow is called the *bus*. The bus refers to the electrical connections that exist between the components of MA. These electrical connections are strips of metal laid down on the sillicon chip. 
We also have I/O devices, which flows between the processor. This could be a keyboard, a mouse, a screen, etc. 

A processor is the *active block of the computer that's responsible for following the instructions making up a programme*. 

Buses are digital connections between functional blocks. They can be *serial* or *parallel*. 

Serial: One bit is transmitted at a time.
Parallel: Several bits are transmitted simultaneously. Usually implemented using several parallel wires. 

Working with Harvard MA. Harvard MA seperates instruction memory from data memory. In Von Neumann architecture there is one memory space for both data and instructions. 
Most modern computers follow the VN architecture. Harvard architecture is commonly found in embedded systems, microcontrollers, and specialized applications. 

Instruction memory will store the programme and data memory will store variables. 

There's a distinction between specialized and generalized computing. Generalized computers are what we usually deal with and are programmable. Specialized computers are designed to do only 1 job. The latter are very fast and low cost and power efficient but not very versatile.  

Some stored programmes devices also have specialized hardware to accelerate certain operations. 
DSPs: Digital signal processors
GPUs: Graphics processing units

- An Embedded system is a computer that is embedded in a larger system that does a very specific job. Embedded systems still use a stored programme micro-architecture. Firmware is software that provdies very low level control of hardware. 
