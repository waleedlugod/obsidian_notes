The basic element is the memory cell which stores a bit.
	select control/wl
read 0         1
write 1        1
hole x         0

RAM is the most common type.
Read write is easy and rapid.
Read write achieved thorugh electrical signals.
Temporary storage only since its volatile.
DRAM and SRAM in computers.

Dynamic RAM is made with cells that store data as charge on capacitors.
DRAM requires periodic charge refreshing to maintain data storage.
Capacitors have a natural tendency to discharge.

Static RAM is a digital device that uses the same logic elements use in the processor.
Bits stored using flip-flop logic gates.
Will store data as long as power is supplied.

DRAM is simpler and smaller than SRAM.
SRAM is somewhat faster than DRAM. SRAM doesn't require a refresh cycle.

Read-only memory has permanent data that cannot be changed.
Nonvolatile.

Read-mostly memory for read operations are more frequent and requires nonvolatile storage.
Data is wired into the chip as part of the fabrication process.

Programmable ROM is nonvolatile and written only once, but is done electrically.

Erasable programmable ROM is read and written electrically, but must be reset first to an initial state via ultraviolet radiation.
Counts as read-mostly memory.
1 transistor per bit.

Electrically Erasable Programmable ROM is read-mostly memory than can be written into any time without erasing prior contents.
Writing takes longer than reading.
2 transistors per bit.

Flash memory uses electrical erasing for erasing blocks in a single action.

Main memory is composed to DRAM chips.
Chips can be grouped to form a memory bank.
Interleaved memory can be made from organizing the memory banks.
Each bank can service a request independently.

Interleaved memory minimizes wait times between reads and writes by not using the same memory bank during contiguous reads and writes.