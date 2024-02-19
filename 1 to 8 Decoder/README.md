## Write VHDL code for 1*8 Decoder

# ** 1*8 Decoder**
This repository contains VHDL code for 1*8 Decoder(- ![#f03c15](demux)) and its corresponding onetoeight_tb (- ![#f03c15](onetoeight_tb)).

### Files
 - - ![#f03c15](onetoeight): VHDL code for the mux entity and architecture
 - - ![#f03c15](onetoeight_tb): VHDL code for the onetoeight_tb entity and architecture.

### 2*1 mux((- ![#f03c15](mux)))
The (- ![#f03c15](mux)) entity represents mux with following ports: 
 - (- ![#f03c15](A,S0,S1,S2)):  input bit
 - (- ![#f03c15](y)): output

### TESTBENCH(onetoeight_tb)
The onetoeight_tb(- ![#f03c15](onetoeight_tb)) is used to verify the functionality of the (- ![#f03c15](demux)) entity. It provides stimulus to the full adder module and observes its outputs.

### Running the TESTBENCH
To run the onetoeight_tb: 

 1. Compile the VHDL file(onetoeight and onetoeight_tb) using a VHDL compiler(e.g., GHDL).
 2. Simulate the compiled design using a simulator(e.g., GTKWAVE)

### Test Cases
The onetoeight_tb includes various test cases to verify the behavior of the 1 to 8 decoder: 
 1. **Test Case 1**:Inputs - ![#f03c15](A='0',S2='0',S1='0',S0='0')
 2. **Test Case 2**:Inputs - ![#f03c15](A='1',S2='0',S1='0',S0='0')
 3. (*Add more test cases as needed*)

### Simulation Duration
 Each test case is simulated for a duration to allow  sufficient time for the computation to finish and the result to stabilize.

 ![Simulation of mux](/1%20to%208%20Decoder/Image_onetoeight.png)