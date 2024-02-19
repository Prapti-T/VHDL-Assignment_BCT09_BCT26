## Write VHDL code for upCounter

# **SEQUENCE DETECTOR**
This repository contains VHDL code for upCounter(- ![#f03c15](TFF)) and its corresponding testbench (- ![#f03c15](tb_counter)).

### Files
 - - ![#f03c15](upcounter.vhdl): VHDL code for the TFF entity and architecture
 - - ![#f03c15](upcounter_tb.vhdl): VHDL code for the tb_counter entity and architecture.

### LCM((- ![#f03c15](sequence)))
The (- ![#f03c15](TFF)) entity represents upCounter with following ports: 
 - (- ![#f03c15](RESET)): Reset input
 - (- ![#f03c15](CLK)): Clock input
 - (- ![#f03c15](T)):  input bit
 - (- ![#f03c15](Q)): output

### Testbench(jk_tb)
The testbench(- ![#f03c15](tb_counter)) is used to verify the functionality of the (- ![#f03c15](TFF)) entity. It provides stimulus to the sequence detector module and observes its outputs.

### Running the Testbench
To run the testbench: 

 1. Compile the VHDL file(upcounter.vhdl and upcounter_tb.vhdl) using a VHDL compiler(e.g., GHDL).
 2. Simulate the compiled design using a simulator(e.g., GTKWAVE)

### Test Cases
The testbench includes various test cases to verify the behavior of the GCD calculator: 
 1. **Test Case 1**:Inputs - ![#f03c15](RST='1')
 2. **Test Case 2**:Inputs - ![#f03c15](RST='0')
 3. (*Add more test cases as needed*)

### Simulation Duration
 Each test case is simulated for a duration to allow  sufficient time for the computation to finish and the result to stabilize.

 ![Simulation of sequence detector](/Up%20Counter/Image_upcounter.jpg)