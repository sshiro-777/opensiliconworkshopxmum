<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

AND, NAND and OR gates are connected to input a and b.

16 flip flops are used to divide the clock speed with 2 outputs, one at the 12th flop and one at the 16th.

## How to test

Set the inputs and check the outputs match with the expected results:
| input IN0 IN1 IN2 | output OUT0 | output OUT4 |
|-------------------|-------------|-------------|
|0 0 0	            |1           |0            |
|0 0 1	            |1           |0            |
|0 1 0	            |1           |0            |
|0 1 1	            |0           |1            |
|1 0 0	            |1           |0            |
|1 0 1	            |0           |1            |
|1 1 1	            |0           |1            |
Set the clock to 0kHz.
