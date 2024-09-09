Capabilities:
* Pipelining
* Branch predictions
* Superscalar execution
* Data flow analysis
* Speculative execution

Pipelining allows a processor to work simultaneously on multiple instructions.
Pipelining doesn't improve latency but generally helps with throughput.
Higher latency per instruction but lower total latency.

Instruction cycle:
1. Fetch
2. Decode
3. Operand fetch
4. Execute
5. Store

Branch prediction: the processor looks ahead in the instructions from memory and predicts which group of instructions are to be processed next.

Superscalar execution is the ability to issue more than one instruction in every processor clock cycle.
Use multiple parallel pipelines but not necessarily multiple cores.

Data flow analysis checks which instructions are dependent on each other to create an optimized schedule of instructions.

Via branch prediction and data flow analysis, processors speculative execute instructions ahead of time.

Memory speed is lower than processor speed so need to compensate for mismatch.