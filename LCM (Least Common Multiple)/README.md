## Write VHDL code for custom processor that calculates Least Common Multiple(LCM) of two numbers

# **LCM (Least Common Multiple)**
This repository contains VHDL code for computing Least Common Multiple(LCM) of two input integers(- ![#f03c15](lcm)) and its corresponding testbench (- ![#f03c15](lcm_tb)).

### Files
 - - ![#f03c15](LCM.vhdl): VHDL code for the lcm entity and architecture
 - - ![#f03c15](LCM_tb.vhdl): VHDL code for the lcm_tb entity and architecture.

### LCM((- ![#f03c15](lcm)))
The (- ![#f03c15](lcm)) entity represents Jk flipflop with following ports: 
 - (- ![#f03c15](RESET)): Reset input
 - (- ![#f03c15](CLK)): Clock input
 - (- ![#f03c15](a)): First input integer
 - (- ![#f03c15](b)): Second input integer
 - (- ![#f03c15](lcm_result)): output

### Testbench(jk_tb)
The testbench(- ![#f03c15](lcm_tb)) is used to verify the functionality of the (- ![#f03c15](lcm)) entity. It provides stimulus to the lcm module and observes its outputs.

### Running the Testbench
To run the testbench: 

 1. Compile the VHDL file(LCM.vhdl and LCM_tb.vhdl) using a VHDL compiler(e.g., GHDL).
 2. Simulate the compiled design using a simulator(e.g., GTKWAVE)

### Test Cases
The testbench includes various test cases to verify the behavior of the LCM: 
 1. **Test Case 1**:Inputs - ![#f03c15](a=45), (- ![#f03c15](b=15))
 2. **Test Case 2**:Inputs - ![#f03c15](a=7), (- ![#f03c15](b=13))
 3. (*Add more test cases as needed*)

### Simulation Duration
 Each test case is simulated for a duration to allow  sufficient time for the computation to finish and the result to stabilize.

 ![Simulation of LCM](/LCM%20(Least%20Common%20Multiple)/Image_LCM.png)
