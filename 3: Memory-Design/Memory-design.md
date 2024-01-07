# Memory Design

First goes through some different types of memory

## Volatile Memory

This is memory that loses its data when power cycled. RAM (Random Access Memory) is the primary type of this; Volatile memory is implemented using RAM. 

There's two main families of RAM - Dynamic RAM (DRAM) and Static RAM (SRAM). When you buy RAM for your computer this is typically DRAM. 

DRAM stores bits as charges on a capacitor. It's dynamic since the bits dissapear when read and need to be refreshed due to capacitor decay. 

SRAM stores bits using cross-coupled inverters. SRAM is faster than DRAM but less dense, so is mainly used for high-speed cache memory within a CPU. 

## Non-Volatile Memory

This is memory that's able to retrieve data after being power cycled. It's used in hard drives and to store instructions in MCUs. 

The primary technology for this has been magnetic disk (spinning magnetic plates) but this is being surpassed by flash memory. Flash memory is faster, quieter, more energy efficient and more reliable. However, it's also more expensive and less secure. Less secure in the sense that when you delete something from flash you can actually read it again, in some cases. 

Predicts that flash memory will be the primary non-volatile memory soon. 

Typically, non-volatile memory is used for the task of secondary storage. Primary storage is used in volatile memory, usually, since non-volatile memory have negative costs like providing lower performance and a limited lifetime compared to volatile access memory. 

 ## Data Memory vs Instruction Memory

 Remember that in Von Neumann Architecture, Data Memory (DM) and Instruction Memory (IM) are stored in the same place. In Harvard Architecture, they are stored seperately. This course focuses, as was mentioned, on Harvard Architecture. 

Data memory allows reading and writing and uses 16 bit addressing.

 The data memory and instruction memory interface are slightly different. 

 DM Interface:
 - Address bus that indexes the region of the memory. Byte level 16 bit addressing. 
 - The 1