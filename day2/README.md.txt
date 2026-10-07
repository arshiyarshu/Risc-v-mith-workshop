# Day 2: Application Binary Interface and Basic Verification Flow

On the second day, we learned more about how a program written in a high-level language such as **C** is converted into instructions that the processor can understand. We went one level deeper into the connection between software and hardware.

We also learned about the **Application Binary Interface (ABI)**. Similar to how an **API** allows applications to use functions provided by software libraries, an ABI provides a way for programs to interact with the system and access hardware-related resources.

The RISC-V ISA can be broadly understood through the **User ISA** and **System ISA**. The user-level instructions are used by normal programs, while system-level operations provide access to resources that are managed by the system.

## Registers in RISC-V

The ABI makes use of registers to pass data and perform operations. RISC-V has **32 general-purpose registers**. The size of each register depends on the architecture:

* **RV32:** XLEN = 32 bits
* **RV64:** XLEN = 64 bits

These registers have specific **ABI names**, which make it easier for programmers and compilers to identify their purpose.

## Types of Registers and Instructions

For the basic integer instruction set, we came across different instruction formats. The main types discussed were:

* **I-Type:** Used for instructions that contain an immediate value along with register operands.
* **R-Type:** Used when the operation works mainly with register operands.
* **S-Type:** Mainly used for instructions that store data from a register into memory.

Understanding these instruction formats helped us see how different operations are represented at the machine level.

Overall, Day 2 helped us understand the role of the **ABI, registers, and instruction formats** in connecting software with the underlying hardware. This gave us a better idea of how programs are actually handled inside a RISC-V processor.
