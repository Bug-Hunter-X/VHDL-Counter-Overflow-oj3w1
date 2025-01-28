# VHDL Counter with Potential Overflow
This repository demonstrates a potential overflow issue in a simple VHDL counter. The counter increments correctly until it reaches 10 but lacks robust handling of potential values exceeding 10. 

The `bug.vhdl` file shows the original code with the potential issue. The `bugSolution.vhdl` file presents a corrected version with improved overflow handling.

This example highlights the importance of careful consideration of data ranges and potential overflow scenarios when designing digital circuits using VHDL.