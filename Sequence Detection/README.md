## Write VHDL code for sequence detector(1011)

# **SEQUENCE DETECTOR**
This repository contains VHDL code for Sequence Detector(- ![#f03c15](sequence)) and its corresponding testbench (- ![#f03c15](sd_tb)).

### Files
 - - ![#f03c15](detector.vhdl): VHDL code for the detector entity and architecture
 - - ![#f03c15](detector_tb.vhdl): VHDL code for the sd_tb entity and architecture.

### SEQUENCEDETECTOR((- ![#f03c15](sequence)))
The (- ![#f03c15](sequence)) entity represents Jk flipflop with following ports: 
 - (- ![#f03c15](RESET)): Reset input
 - (- ![#f03c15](CLK)): Clock input
 - (- ![#f03c15](a)):  input bit
 - (- ![#f03c15](z)): output

### Testbench(jk_tb)
The testbench(- ![#f03c15](sd_tb)) is used to verify the functionality of the (- ![#f03c15](sequence)) entity. It provides stimulus to the sequence detector module and observes its outputs.

### Running the Testbench
To run the testbench: 

 1. Compile the VHDL file(detector.vhdl and detector_tb.vhdl) using a VHDL compiler(e.g., GHDL).
 2. Simulate the compiled design using a simulator(e.g., GTKWAVE)

### Test Cases
The testbench includes various test cases to verify the behavior of the sequence detector: 
 1. **Test Case 1**:Inputs - ![#f03c15](a='1')
 2. **Test Case 2**:Inputs - ![#f03c15](a='0')
 3. **Test Case 3**:Inputs - ![#f03c15](a='1')
 4. **Test Case 4**:Inputs - ![#f03c15](a='1')
 5. (*Add more test cases as needed*)

### Simulation Duration
 Each test case is simulated for a duration to allow  sufficient time for the computation to finish and the result to stabilize.

 ![Simulation of sequence detector](/Sequence%20Detection/Image_detector.png)