## Write VHDL code for 2*4 DECODER

# **2*4 DECODER**
This repository contains VHDL code for 2*4 decoder(- ![#f03c15](decoder)) and its corresponding testbench (- ![#f03c15](DECODER_tb)).

### Files
 - - ![#f03c15](DECODER.vhdl): VHDL code for the decoder entity and architecture
 - - ![#f03c15](DECODER_tb.vhdl): VHDL code for the DECODER_tb entity and architecture.

### 2*4 DECODER((- ![#f03c15](decoder)))
The (- ![#f03c15](decoder)) entity represents decoder with following ports: 
 - (- ![#f03c15](a1,a0,e)):  input bit
 - (- ![#f03c15](q3,q2,q1,q0)): output

### Testbench(DECODER_tb)
The testbench(- ![#f03c15](DECODER_tb)) is used to verify the functionality of the (- ![#f03c15](decoder)) entity. It provides stimulus to the full adder module and observes its outputs.

### Running the Testbench
To run the testbench: 

 1. Compile the VHDL file(DECODER.vhdl and DECODER_tb.vhdl) using a VHDL compiler(e.g., GHDL).
 2. Simulate the compiled design using a simulator(e.g., GTKWAVE)

### Test Cases
The testbench includes various test cases to verify the behavior of the 2*4 decoder: 
 1. **Test Case 1**:Inputs - ![#f03c15](a0='0',a1='0',e='1')
 2. **Test Case 2**:Inputs - ![#f03c15](a0='1',a1='0',e='1')
 3. (*Add more test cases as needed*)

### Simulation Duration
 Each test case is simulated for a duration to allow  sufficient time for the computation to finish and the result to stabilize.

 ![Simulation of decoder](/2x4%20decoder/Images_DECODER.png)