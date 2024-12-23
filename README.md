### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'
program:
LOGIC GATES

GATE LEVEL MODEL:
module log_gat(a,b,c1,c2,c3,c4,c5,c6,c7);
input a,b;
output c1,c2,c3,c4,c5,c6,c7;
not g1(c1,a);
and g2(c2,a,b);
or g3(c3,a,b);
nand g4(c4,a,b);
nor g5(c5,a,b);
xor g6(c6,a,b);
xnor g7(c7,a,b);
endmodule

developed name:hariharasudhan N

Register Number:24900208
 
**Logic symbol & Truthtable**<br>
![380986504-994fd73b-8a02-4ea0-8361-388ef783a1fd](https://github.com/user-attachments/assets/61d78791-1b62-4ffc-b3d6-9f876a1d55a9)


**RTL realization Output:**<br>
![380986107-3ba20975-13bf-4ef8-8921-d19471dbe230](https://github.com/user-attachments/assets/4881b197-1027-4e48-b3c4-8d0bf8f6c177)




**RTL**)
![380986000-184804d8-4e97-4732-bbc8-f3aff6709d59](https://github.com/user-attachments/assets/f164664b-7156-440f-8fb6-675d7e212f29)



**Result:**
The study of basic gates involves understanding the fundamental logic gates used in digital electronics. These gates perform logical operations based on binary inputs (0 and 1) and produce a specific output. Below is an overview of the basic gates and their results:



