# Approximate_Adder
Verilog code for designing an approximate adder:
The repository contains the verilog code for designing a high accuracy approximate adder, based on the paper "A high-accuracy approximate adder with correct sign calculation" (DOI link- https://doi.org/10.1016/j.vlsi.2017.09.003). 
The code is for the implementation of the proposed adder (a 12-bit implementation has been done) with error correction. 
A step-by-step module-level implementation has been provided.
Step 1: Open the Half_Adder.txt file, and using the code create a binary adder(half adder) module in your desired Verilog environment.
Step 2: Using the binary adder module, create the PG_Generator module, as shown in PG_Generator.txt file.
Step 3: Then create the two other modules ( Carry_Generator and Sub_Adder) using the files with the same name. 
Step 4: Using these 3 modules, we create a block of the Approximate Adder, which will add 4 bits. 3 such blocks are connected to form a 12-bit Adder. Follow the code in the Approximate_Adder_Block.txt file for creating one such block.
Final Step: Connect three of the blocks, to form the 12-bit adder. Follow the file named Approximate_Adder.txt for the creation of such a block.
