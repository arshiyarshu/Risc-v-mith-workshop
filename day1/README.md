Day 1: Instruction Set Architecture \& GNU Toolchain

Introduction

The first session was mainly about getting started with the RISC-V environment. We were introduced to the VSD-IAT platform and learned how to work with the lab setup. This session gave us the basic knowledge needed for the experiments that would be done in the next few days.

We learned that a program does not directly become machine code. First, a program written in a language such as C is converted into assembly instructions. These instructions are then converted into machine or binary code, which can be understood by the processor.

We also discussed how integers are stored in a computer and the limits of different types of numbers. In the RV64 architecture:

A word consists of 32 bits.
A double word consists of 64 bits.
An unsigned 64-bit number can have values from (0) to (2^{64}-1).
A signed 64-bit number can have values from (-2^{63}) to (2^{63}-1).

We were also introduced to RV64I, which is the basic integer instruction set used in the RV64 RISC-V architecture.

Overall, this session helped us understand the basic RISC-V setup, how programs are converted into instructions, and how integer values are represented. It was a useful starting point for the practical work we would be doing in the upcoming sessions.

