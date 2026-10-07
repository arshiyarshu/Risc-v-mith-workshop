# Day 4: RISC-V CPU Core Implementation

On the fourth day, we started working on the **RISC-V CPU core** and learned about the basic stages involved in the execution of an instruction.

The CPU works through different stages such as **Fetch, Decode, and Execute**. In the **Fetch stage**, the instruction is taken from memory. In the **Decode stage**, the instruction is understood and the required data is identified. Finally, in the **Execute stage**, the actual operation is performed.

Initially, we designed a **single-cycle processor**, where an instruction completes its required operations within one clock cycle.

After understanding the single-cycle design, we moved towards **pipelining the processor**. The instructions were divided into different stages using separate `@` blocks. This allowed different instructions to be processed in different stages at the same time.

This experiment helped us understand the basic structure of a **RISC-V processor**, how an instruction moves through the CPU, and how pipelining can be used to improve processor performance.

Overall, Day 4 gave us practical knowledge about designing a basic RISC-V CPU core and understanding the flow of instructions through its different stages.
