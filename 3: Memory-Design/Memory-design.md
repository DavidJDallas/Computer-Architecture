# Memory Design

First goes through some different types of memory

## Volatile Memory

This is memory that loses its data when power cycled. RAM (Random Access Memory) is the primary type of this; Volatile memory is implemented using RAM. 

There's two main families of RAM - Dynamic RAM (DRAM) and Static RAM (SRAM). When you buy RAM for your computer this is typically DRAM. 

DRAM stores bits as charges on a capacitor. It's dynamic since the bits dissapear when read and need to be refreshed due to capacitor decay. 

SRAM stores bits using cross-coupled inverters. SRAM is faster than DRAM but less dense, so is mainly used for high-speed cache memory within a CPU. 

## Non-Volatile Memory

This is memory that's able to retrieve data after being power cycled. It's used in hard drives and to store instructions in MCUs. 

The primary technology for this has been magnetic disk (spinning magnetic plates) but this is being surpassed by flash memory. Flash memory is faster, quieter, more energy efficient and more reliable. However, it's also more expensive and less secure. 