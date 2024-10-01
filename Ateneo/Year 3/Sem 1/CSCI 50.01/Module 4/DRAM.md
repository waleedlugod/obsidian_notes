Basic building blocks of memory.
Constrained by memory architecture and interface to the memory bus.

Insert high-speed SRAM cache between DRAM and processor to increase speed.

SDRAM
Synchronous DRAM exchanges data with the processor synchronous to an external clock.
Processor can safely do other tasks while SDRAM is processing the request.

Asynchronous DRAM, DRAM reads and writes after a delay (access time)
During acess-time delay: activating the high capacitance of the row and column line; sensing data; routing data through the output buffers

DDR-SDRAM
Double data rate SDRAM
Data transfer is synchronized toboth the rising and falling edge of the clock.

Prefetch buffer: cache located on the SDRAM chip.
Enables the chip to pre-position bits to be placed on the data bus.

Prefetch buffer size determines words of data fetched.
Since DRAM is slower than IO bus, information is accessed in parallel and serializing it out the interface through a mux.

New generation of SDRAM have greater capacity but core speed hasnt changed.