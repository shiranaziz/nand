bartsimp, lisasimp
===============================================================================
Bart Simpson, ID 011111111, bart@cs.huji.ac.il
Lisa Simpson, ID 022222222, lisa@cs.huji.ac.il
===============================================================================

                           Project 2 - Combintional Chips
                           ----------------------- 
  

Submitted Files
---------------
README - This file.
HalfAdder.hdl - Chip,Computes the sum of two bits. 
	input: 1-bit
	output: 2- bit, sum and carry 
FullAdder.hdl - Chip, Computes the sum of three bits.
	input: 3 -bit, three numbers
	output: 2- bit, sum and carry 
Add16.hdl - Chip, Adds two 16-bit values
	input: 32 -bit, two nombers of 16-bit each
	output: the sum of the numbers (arithmetic addition)
Inc16.hdl - Chip, 16-bit incrementer
	input: 16 -bit
	output: in + 1 (arithmetic addition)
ALU.hdl - The ALU, Arithmetic Logic Unit, cumpute the function 
given in the input between two numbers.
	input: 38 -bit,two numbersof 16-bit,
	6-bit then function we need operate, every bit represents other part of the function 
	output: 18 - bit, 16- bit the result of the calculation,
	1- bit if the result came 0, 1-bit if the result is less then 1
ShiftLeft.hdl - Chip, 16-bit multiply by 2
	input: 16 -bit
	output: 2*in (arithmetic addition)
ShiftRight.hdl -divde by 2 , preserves the sign and move on bit right
	input: 16 -bit
	output: in/2 (arithmetic addition)
	
Mask.hdl - preserves the inserted value 
	input: 1-bit
	output: 1-bit 
 
Remarks
-------
* The chip was actually implemented by simply using an Or chip. cool!
