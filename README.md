# Full_adder
RTL Design Full_adder using Verilog @Xilinx vivado

Full Adder is a digital circuit that adds three single-digit binary numbers. This is a three-input and two-output digital circuit. 

For three single-bit binary numbers A, B, and D; the full adder circuit generates two single-bit binary outputs S (Sum), and C (Carry).

Full Adder was made to overcome the limitations of Half Adder.

Full Adders Uses

- Digital Diaries
- Digital Calculator 
- Digital Computer
- Arithmetic Logic Unit (ALU) of Microprocessors.

**Operation of Full Adder**

Full adder takes three inputs namely A, B, and Cin. Where, A and B are the two binary digits, and Cin is the carry bit from the previous stage of binary addition. The sum output of the full adder is obtained by XORing the bits A, B, and Cin. While the carry output bit (Cout) is obtained using AND and OR operations.

**Truth Table of Full Adder**

Truth table is one that indicates the relationship between input and output variables of a logic circuit and explains the operation of the logic circuit. The following is the truth table of the full-adder circuit −

      Inputs	Outputs
      A	B   Cin	S  Cout 
      0	0    0  	0    0
      0	0    1	1    0
      0	1    0	1    0
      0	1    1	0    1
      1	0    0	1    0
      1	0    1	0    1
      1	1    0	0    1
      1	1    1	1    1
Hence, from the truth table, it is clear that the sum output of the full adder is equal to 1 when only 1 input is equal to 1 or when all the inputs are equal to 1. While the carry output has a carry of 1 if two or three inputs are equal to 1.

![Full_adder](https://github.com/bhupathi390/Full_adder/blob/4bd9c1b36d190c9742a4aad7d78e68f9debc37a9/Full-Adder.jpg)



**Advantages of Full Adder**

The following are the important advantages of full adder over half adder −

Full adder provides facility to add the carry from the previous stage.
The power consumed by the full adder is relatively less as compared to half adder.
Full adder can be easily converted into a half subtractor just by adding a NOT gate in the circuit.
Full adder produces higher output that half adder.
Full adder is one of the essential part of critic digital circuits like multiplexers.
Full adder performs operation at higher speed.


**Applications of Full Adder**

The following are the important applications of full adder −

Full adders are used in ALUs (arithmetic logic units) of CPUs of computers.
Full adders are used in calculators.
Full adders also help in carrying out multiplication of binary numbers.
Full adders are also used to realize critic digital circuits like multiplexers.
Full adders are used to generate memory addresses.
Full adders are also used in generation of program counterpoints.
Full adders are also used in GPU (Graphical Processing Unit).
