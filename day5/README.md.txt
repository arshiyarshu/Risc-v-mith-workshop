# Day 5: Pipelined RISC-V Core

On the fifth day, we continued working on the RISC-V processor that we designed earlier. The single-stage CPU was modified into a **3-stage pipelined processor**. The main aim was to understand how pipelining can divide the work into different stages and allow instructions to move through the processor efficiently.

We also implemented a simple application where the processor calculates the **sum of 9 numbers**.

### Converting the CPU into a Pipelined Design

We used the **timing abstraction feature of TL-Verilog** to convert the non-pipelined CPU into a pipelined version. This feature makes it easier to change the timing and add pipeline stages without changing the basic functionality of the design.

It also reduces the chances of introducing functional errors while retiming the design. We learned that timing abstraction is one of the useful features of TL-Verilog for designing and modifying pipelined hardware.

## Complete RV32I Core

After working with the basic pipeline, we developed a more complete **RV32I RISC-V processor core**.

The main features added were:

* A **4-stage pipelined RISC-V core** was developed with support for the basic RV32I integer instructions.
* **Data memory** was added to support load and store instructions.
* Additional instruction decoding logic was included to identify and execute load and store operations.
* **Register bypassing** was implemented to handle data hazards that can occur between instructions in a pipeline.
* **Squashing** was used to handle hazards related to branching.
* The pipelined processor was tested using assembly programs that included load and store operations.
* Support for **JAL and JALR jump instructions** was also added.

These additions helped us understand how different features are combined to build a more complete RISC-V processor.

Overall, Day 5 was mainly focused on understanding **pipelining, timing abstraction, hazards, data memory, and jump instructions**. By the end of the session, we had developed a more complete **4-stage RV32I pipelined CPU core** and tested its functionality.
