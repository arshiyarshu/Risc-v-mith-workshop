# Day 3: Introduction to TL-Verilog and Makerchip

On the third day, we were introduced to **TL-Verilog (Transaction-Level Verilog)** and learned how it can be used to design digital circuits. We started with simple **combinational and sequential logic** and implemented them using TL-Verilog.

We also worked with the **Makerchip IDE**, which is an open-source online tool developed by **Redwood EDA**. It provides an easy environment for writing and testing hardware designs.

At the end of the session, we implemented a **sequential cyclic calculator**, which helped us understand how sequential logic works over multiple clock cycles.

## What is TL-Verilog?

TL-Verilog is an extension of **SystemVerilog** that provides a simpler and higher-level way of describing hardware designs. It reduces the amount of code required and makes hardware design easier to understand.

In TL-Verilog, the design is mainly viewed as a **pipeline of transactions**. Data enters the pipeline as an input and moves through different stages before producing the required output.

## Advantages of TL-Verilog

Some of the important advantages we learned are:

* It requires **less code**, which makes the design easier to write and maintain.
* It reduces the possibility of errors because many hardware details are automatically handled.
* In pipelined designs, **registers, flip-flops, and staged signals** can be automatically inferred based on the design context.
* Different pipeline stages can be added easily without changing the basic working of the logic.
* The **validity feature** makes debugging easier and helps in creating cleaner and more reliable designs.
* It also supports better **error checking** and can help with **automatic clock gating**.

Overall, Day 3 gave us a basic understanding of **TL-Verilog and Makerchip**. The practical exercises helped us see how combinational and sequential circuits can be designed in a simpler way using a higher-level hardware description approach.
