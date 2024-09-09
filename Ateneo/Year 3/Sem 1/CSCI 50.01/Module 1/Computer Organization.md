# Computer Architecture
*Structure* is the way in which components are interrelated
*Function* is the operation of each individual component
*Instruction set architecture (ISA)* defines instruction formats, opcodes, registers, and memory; effect of executing instructions on registers and memory; and algorithm for controlling instruction execution.
*Computer architecture* refers to the different attributes or features of a computer system.

# Computer Organization
*Computer organization* refers to the operational units and their interconnections that realize the architectural specifications.
**Architecture** says **what** is supported and **organization** says **how** to support it.
Organizational attributes include hardware details, interface between computer and peripherals, and memory technology used.
It is possible to have identical architecture but with differences in organization.

# Structure and function
Arranged in a hierarchical system.
Behavior depends on abstracted characterization of the system at the lower level.
*Function* is the operation of each individual component ~ architecture.
*Structure* is the way components are interrelated ~ organization  .

Basic functions of a computer:
1. Data processing
	1. Few fundamental types of data processing.
2. Data storage
	1. Data storage functions: short-term, long-term.
3. Data movement
	1. Input-output is the process by which data is received or delivered directly to a computer.
	2. Data communications is the process by which data are moved over longer distances, to or from a remote device.
4. Control
	1. A control unit manages the computer's resources and directs the performance of its parts in response to instructions.

## Structure
Main structural components: Central processing unit, main memory, I/O, system interconnection

*CPU* controls the operations of the computer and performs its data processing functions.
*Main memory* stores short-term data.
*I/O* move data between the computer and its external environment.
*System interconnection* provides communication among the CPU, main memory, and I/O e.g. *system bus*.

### CPU
Main structural components: control unit, arithmetic and logic unit, registers, CPU interconnection.

Control unit directs the operation of the CPU.
Registers provide internal storage to the CPU; **not** main memory.
ALU performs the data processing functions.
CPU interconnection provides communication among the CPU, ALU, and registers.

## Multicore Computer Structure
When multiple processing units all reside on a single chip, the term is a *multicore computer*.
Each processing unit is called a core.

Processor is the computer component that interprets and executes instructions.
It refers to a piece of silicon containing one or more cores. If a processor contains multiple cores, it is called *multicore processor*.