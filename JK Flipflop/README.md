## Write VHDL code for JK flipflop

# **JK Flip-Flop**
This repository contains VHDL code for JK flip-flop (- ![#f03c15](Jk)) and its corresponding testbench (- ![#f03c15](JK_tb)).

### Files
 &#9679; JK.vhdl: VHDL code for the jk entity and architecture
 &#9679; JK_tb.vhdl: VHDL code for the jk_tb entity and architecture.

### JK Flipflop((- ![#f03c15](Jk)))
The (- ![#f03c15](Jk)) entity represents Jk flipflop with following ports: 
 &#9679; (- ![#f03c15](RESET)): Reset input
 &#9679; (- ![#f03c15](CLK)): Clock input
 &#9679; (- ![#f03c15](J)): J input
 &#9679; (- ![#f03c15](K)): K input
 &#9679; (- ![#f03c15](Q and Q0)): output

### Testbench(jk_tb)
The testbench(- ![#f03c15](jk_tb)) is used to verify the functionality of the (- ![#f03c15](jk)) entity. It provides stimulus to the Jk flipflop and observes its outputs.

### Running the Testbench
To run the testbench: 

 1. Compile the VHDL file(JK.vhdl and JK_tb.vhdl) using a VHDL compiler(e.g., GHDL).
 2. Simulate the compiled design using a simulator(e.g., GTKWAVE)

### Test Cases
The testbench includes various test cases to verify the behavior of the GCD calculator: 
 1. **Test Case 1**:Inputs - ![#f03c15](J='0'), (- ![#f03c15](K='0'))
 2. **Test Case 2**:Inputs - ![#f03c15](J='1'), (- ![#f03c15](K='0'))
 3. **Test Case 3**:Inputs - ![#f03c15](J='0'), (- ![#f03c15](K='1'))
 4. **Test Case 4**:Inputs - ![#f03c15](J='1'), (- ![#f03c15](K='1'))
 5. (*Add more test cases as needed*)

### Simulation Duration
 Each test case is simulated for a duration to allow  sufficient time for the computation to finish and the result to stabilize.

 ![Simulation of JK flipflop](/JK%20Flipflop/Image_gcd.png)


