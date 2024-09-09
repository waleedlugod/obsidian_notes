hertz: cycle per second
clock speed: instructions per second
giga = billion

5 clock cycles per instruction
	ADD x y
	 MUL a b
	 AND A B

1. get ins
2. decode
3. do operation
4. get result
5. save result

long distance causes delays
RC circuit = delays
RC = resistance capacitor
clock and output might not be synced up

1 = 4.8V – 5V
0 = 0V – 0.2V
*propagation delay (t_pd)*: **upper bound** between **new valid inputs** and **new valid outputs** in time; how long it takes for the circuit to "settle"
*contamination delay (t_cd)*: **lower bound** between **invalid inputs**  and **invalid outputs** in time; how long it takes for one invalid signal to mess up the result

lower *feature size* is a better transistor.
t_pd and the t_cp are the maximum and minimum paths from input to output of a circuit respectively

*Fan-in*: increased number of inputs for a single gate.
*Fan-out*: increased connections from an output.

t_pd guarantees safe times to check output and start changing input.

Delays dictate a processor's speed, frame rate, etc.