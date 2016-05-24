# Verilog-Projects
This is a Verilog repository that contains source code for past labs and projects.

## To Run & Test
##### 1. Xilinx ISE

##### 2. [EDA Playground](http://www.edaplayground.com/home)
- Login through Google or Facebook to save and run modules and test benches
- Testbench + Design: SystemVerilog/Verilog
- Tools & Simulators: Icarus Verilog 0.9.7

## Fall 2015

- [Half Adder](/Project 1 – Introduction to Xilinx): This half adder adds two one-bit binary numbers and outputs the sum of the two bits and the carry.

- [Full Adder](/Project 2 – Combinational Logic/full_adder): This full adder takes 3-bits for the input as A, B and Carry In. It outputs 2-bits as Sum and Carry Out. The Sum will be the lowest value output and the Carry Out is the highest value output as well as where other full adders could be joined together. 

- [Four Bit Ripple Adder](/Project 2 – Combinational Logic/four_bit_ripple_adder): This 4-bit adder takes advantage of the full adder module by taking four full  adders and linking them together to add 2 four bit inputs. In the 4-bit adder, the first carry bit is set to zero because there was no initial carry bit as the input. 

- [Four Bit Look Ahead Adder](/Project 2 – Combinational Logic/four_bit_look_ahead_adder): This 4-bit look ahead adder is an improved implementation of a 4-bit ripple adder by eliminating the propagation delay found in the ripple 4-bit adder. For each output, this implementation computes each previous carry simultaneously instead of waiting for the previous adder block to yield a carry. In this adder, the first carry bit is set to zero and simplified the logic because there was no initial carry bit as the input. While this implementation uses more gates and more complex logic to accomplish the same task as the ripple adder, this implementation would add two 4-bit numbers faster than the ripple version.

- [3-bit Comparator](/Project 2 – Combinational Logic/three_bit_comparator): This 3-bit comparator requires 2 three bit inputs and outputs whether the first input is greater than / less than / or equal to the second input. In practice, the 3-bit comparator would compare two numbers and output the relation between them. To verify this module, the binary input bits were converted into their decimal representation and compared mathematically, example: inputs of 010 and 010 represent, 2 and 2, which the module would output 001 for GT, LT, and EQ, respectively. 

- [4-16 Decoder](/Project 2 – Combinational Logic/dec_4_to_16): This 4-to-16 decoder takes one four bit input and outputs the sixteen bit representation of the input. This module uses the concept of one-hot decoding where each output would have one output that would correspond to the input. An application for this decoder would be to convert a four bit binary to its hexadecimal representation. To verify this module, the input’s binary bits were converted into their decimal representation and compared to the output’s decimal representation to see if they matched.

- [Priority Encoder](/Project 2 – Combinational Logic/priority_encoder): This priority encoder takes one four bit input and outputs the binary representation of the index of the active input bit with the highest priority. In addition, the module will indicate if the output generated is valid by toggling the valid bit, VLD. This solves the issue of having two inputs active at the same time by having the input of the highest priority take precedence.

- [4-1 Multiplexer](/Project 2 – Combinational Logic/mux_four_to_one): This 4-1 multiplexer takes an input of four bits and another input of two bits and outputs the selected input. In this module, the two bits are the select bits that would select which one the inputs should be designated as the output. 

- [Traffic Light Controller](/Project 3 – Traffic Light Controller): The aim of this project is to design a digital controller to control traffic at an intersection of a busy main street (North-South) and an occasionally used side street (East-West).

## Fall 2016

Coming Soon...