Manipulate discrete information (finite elements).
Represented in binary
Examples: digital telephone, digital computer

# Digital Computers
CPU:
* Control unit
* arithmetic logic unit (ALU)
* Registers
Main memory
Solid state storage
I/O:
* Keyboard
* Printer

# Binary Signals
Two states
Bit: smallest unit
Byte: eight-bit group

# Why Computers Use Binary
Easily represented with transistors, and easy to fabricate with silicon
Millions can be put into a tiny chip
Unambiguous signal

# Analog Signal
Smooth and ambiguous, but can be converted to binary by setting a threshold
A filter can be used to reduce noise
# Radix conversion
Repeatedly divide and note the remainder
## Binary to octal
Group into 3 bits with respect to the decimal point
## Octal to binary
Replace each octal digit with three bits
## Binary <-> Hexadecimal
Same with octal but with 4 bits

# Binary Logic
AND: all inputs are true; multiplication
OR: any input is true; addition
NOT: input is not true

# Complements
(r^n-1) - N -> r-1 complement
r^n - N -> r complement
used to simplify subtraction

## Subtraction unsigned
M > N: M + N'; discard end carry
N > M: -(M + N')

# Negative binary
systems:
* signed magnitude
* one's complement
* two's complement

## Signed magnitude
leftmost bit is sign
remaining bits are absolute magnitude
-128 : +127

## Signed one's complement
leftmost bit is sign
negative is one's complement of positive
6 = 00000110
-6 = 11111001

## Signed two's complement
leftmost bit is sign
negative is obtained by taking two's complement of positive number

# Codes
## Binary-coded decimal (BCD):
only 10 of the 4-bit combinations are used
intuitive decimal

4 + 8 = 12
0100 + 1000 = 1100 (not in BCD)
1100 + 0110 (6) = 10010 (12)
if beyond 9: add 6