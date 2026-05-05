16-bit ALU Design with Basic Testbench and Flag Support

Project Description
This project implements a 16-bit Arithmetic Logic Unit (ALU) in Verilog.  
It supports arithmetic, logical, and shift operations along with mandatory status flags.  
The design is verified using a testbench and simulated in Cadence tools.

Supported Operations
- Addition (A + B)
- Subtraction (A – B)
- AND, OR, XOR, NOT
- Logical Left Shift, Logical Right Shift

Status Flags
Z (Zero): Result is zero  
C (Carry/Borrow): Carry out or borrow  
N (Negative): MSB of result  
V (Overflow): Signed overflow detection  


Testbench
- Written in Verilog ("alu_tb.v")  
- Applies multiple test cases  
- Displays outputs using "$display" 
- Verifies correctness manually or via conditions  

Code 
ALU Module
[ALU Code](code%201.jpeg)

Testbench Module
[Testbench Code](code%202.jpeg)

Block Diagram
[Block Diagram](block%20diag.jpeg)

Waveform
[Waveform](waveform.jpeg)
