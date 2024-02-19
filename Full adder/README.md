## Write VHDL code for Full adder

# **FULL ADDER**
This repository contains VHDL code for Full Adder(- ![#f03c15](or_gate)) and its corresponding testbench (- ![#f03c15](fa_test)).

### Files
 - - ![#f03c15](FULLADDER.vhdl): VHDL code for the or_gate entity and architecture
 - - ![#f03c15](FULLADDER_tb.vhdl): VHDL code for the fa_test entity and architecture.

### FULL ADDER((- ![#f03c15](or_gate)))
The (- ![#f03c15](or_gate)) entity represents upCounter with following ports: 
 - (- ![#f03c15](X)):  input bit
 - (- ![#f03c15](Y)):  input bit
 - (- ![#f03c15](Z)): output

### Testbench(fa_test)
The testbench(- ![#f03c15](fa_test)) is used to verify the functionality of the (- ![#f03c15](or_gate)) entity. It provides stimulus to the full adder module and observes its outputs.

### Running the Testbench
To run the testbench: 

 1. Compile the VHDL file(FULLADDER.vhdl and FULLADDER_tb.vhdl) using a VHDL compiler(e.g., GHDL).
 2. Simulate the compiled design using a simulator(e.g., GTKWAVE)

### Test Cases
The testbench includes various test cases to verify the behavior of the JK FLIPFLOP: 
 1. **Test Case 1**:Inputs - ![#f03c15](A='0',B='0',Cin='1')
 2. **Test Case 2**:Inputs - ![#f03c15](A='0',B='1',Cin='0')
 3. (*Add more test cases as needed*)

### Simulation Duration
 Each test case is simulated for a duration to allow  sufficient time for the computation to finish and the result to stabilize.

 ![Simulation of full adder](/Full%20adder/Image_full_adder.png)