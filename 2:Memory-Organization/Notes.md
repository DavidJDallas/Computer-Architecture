# Memory Organization

We always use base 2 when talking about memory. 

Conceptually, memory is just a big array of bytes. The memory address indexes the particular value in memory we want to access. 

Memory space can be grouped into multi-byte chunks called *words*. We have two possibilites for addressing:
1) Word addressing - words are selected using word indices.
2) Byte addressing - words are selected using the smallest byte index in that word. 


Big Endian vs Little Endian

This refers to 2 different systems for indexing the bytes that make up a single word. For both, bits within a byte are ordered the same. Most significant bit  (MSB) is where   