## Write VHDL code for 2*1 MULTIPLEXER

# ** 2*1 Multiplexer**
This repository contains VHDL code for 2*1 multiplexer(- ![#f03c15](mux)) and its corresponding testbench (- ![#f03c15](testbench)).

### Files
 - - ![#f03c15](twotoone_mux.vhdl): VHDL code for the mux entity and architecture
 - - ![#f03c15](twotoone_mux_tb.vhdl): VHDL code for the testbench entity and architecture.

### 2*1 mux((- ![#f03c15](mux)))
The (- ![#f03c15](mux)) entity represents mux with following ports: 
 - (- ![#f03c15](A0,A1,S0)):  input bit
 - (- ![#f03c15](z)): output

### Testbench(testbench)
The testbench(- ![#f03c15](testbench)) is used to verify the functionality of the (- ![#f03c15](mux)) entity. It provides stimulus to the full adder module and observes its outputs.

### Running the Testbench
To run the testbench: 

 1. Compile the VHDL file(twotoone_mux.vhdl and twotoone_mux_tb.vhdl) using a VHDL compiler(e.g., GHDL).
 2. Simulate the compiled design using a simulator(e.g., GTKWAVE)

### Test Cases
The testbench includes various test cases to verify the behavior of the 2*1 mux: 
 1. **Test Case 1**:Inputs - ![#f03c15](S0='0',A0='0',A1='0')
 2. **Test Case 2**:Inputs - ![#f03c15](S0='0',A0='0',A1='1')
 3. (*Add more test cases as needed*)

### Simulation Duration
 Each test case is simulated for a duration to allow  sufficient time for the computation to finish and the result to stabilize.

 ![Simulation of mux](/2x1%20Multiplexer/Image_twotoone.png)