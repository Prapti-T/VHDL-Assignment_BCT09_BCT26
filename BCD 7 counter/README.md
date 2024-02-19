## Write VHDL code for BCD 7 COUNTER

# **BCD 7 COUNTER**
This repository contains VHDL code for BCD 7 COUNTER(- ![#f03c15](bcd_seg)) and its corresponding testbench (- ![#f03c15](BCD_tb)).

### Files
 - - ![#f03c15](BCD.vhdl): VHDL code for the bcd_seg entity and architecture
 - - ![#f03c15](BCD_tb.vhdl): VHDL code for the BCD_tb entity and architecture.

### BCD 7 COUNTER((- ![#f03c15](bcd_seg)))
The (- ![#f03c15](bcd_seg)) entity represents upCounter with following ports: 
 - (- ![#f03c15](b0,b1,b2,b3)):  input bit
 - (- ![#f03c15](a,b,c,d,e,f,g)): output

### Testbench(BCD_tb)
The testbench(- ![#f03c15](BCD_tb)) is used to verify the functionality of the (- ![#f03c15](bcd_seg)) entity. It provides stimulus to the full adder module and observes its outputs.

### Running the Testbench
To run the testbench: 

 1. Compile the VHDL file(BCD.vhdl and BCD_tb.vhdl) using a VHDL compiler(e.g., GHDL).
 2. Simulate the compiled design using a simulator(e.g., GTKWAVE)

### Test Cases
The testbench includes various test cases to verify the behavior of the BCD 7 counter

### Simulation Duration
 Each test case is simulated for a duration to allow  sufficient time for the computation to finish and the result to stabilize.

 ![Simulation of full adder](/BCD%207%20counter/Image_BCD.png)