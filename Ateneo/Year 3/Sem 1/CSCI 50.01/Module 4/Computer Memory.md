Location is whether memory is internal or external.
Internal refers to devices like main memory.
External memory refers to peripherals such as disk drives including "internal" SSD.

Capacity is the maximum amount of memory.

Word is the natural unit of organization in memory.
Size is number of bits used to represent an integer.

For some systems the addressable unit is the word.

Unit of transfer refers to how much data can be read or written into memory at a time.
For internal memory, this is equal to the number of electrical lines into and out of the memory module
For external memory, this is a block, which is a significantly larger unit than a word.

Method of accessing:
1. Sequential access
2. Direct access
3. Random access
4. Associative

Sequential access for tape drives.
Memory organized into units of data called records.
Access made in linear sequence.
Access time is variable.

Direct access are like disks in hard disk drives.
Uses shared read-write mechanism, but individual blocks/records have unique addresses.
First reach general vicinity, then use sequential searching.
Access time is variable.

Random access like main memory, some cache, SSD.
Each addressable location has a unique, physically wired-in addressing mechanism.
Access time is constant and independent of the sequence of prior access.

Associative used in some caches.
Also a random access type of memory, but compares to desired bit locations.
Like fuzzy find.

 Performance parameters:
 1. Access time or latency: time it takes to perform an operation. For ram, how fast data can be stored from the instant it is presented. For non-ram, it is time to takes to position the read-write mechanism.
 2. Memory cycle time: access time + addition time before a second access can start. Additional time required if data is read destructively and data needs to be regenerated. Applies to ram and is concerned with the system bus.
 3. Transfer rate: rate that data can be read or written. For ram, reciprocal of memory cycle time. For non-ram, to_to_read_write = average_access_time + (bits / transfer_rate_bits_per_second)

Physical types:
* semiconductor (ram, ssd)
* magnetic surface memory (disks, tapes)
* optical (blu-ray)
* magneto-optical (Sony MiniDiscs)

Physical characteristics:
* volatile: data decays naturally or lost when power is off
* nonvolatile: data remains without deterioration
* nonerasable: data cannot be altered without destroying the storage unit
Semiconductor can be volatile or nonvolatile
Magnetic-surface memory is nonvolatile.
Nonerasable memory must be nonvolatile.

Organization refers to the physical arrangement of bits for form words. Not the same as endianness