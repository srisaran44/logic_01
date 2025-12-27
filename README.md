AIM:

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

Equipments Required:

Software – Quartus prime

Theory

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

AND gate

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB Y= A.B

OR gate

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation. Y= A+B

NOT gate

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs. Y= A'

NAND gate

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion. Y= (AB)’

NOR gate

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion. Y= (A+B)’

Ex-OR gate

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation. Y= A⊕B

Ex-NOR gate

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion. Y= A⊕B

Procedure

Type the program in Quartus software.

Compile and run the program.

Generate the RTL schematic and save the logic diagram.

Create nodes for inputs and outputs to generate the timing diagram.

For different input combinations generate the timing diagram.

PROGRAM

module log_gat(a,b,c1,c2,c3,c4,c5,c6,c7);
input a,b;
output c0,c1,c2,c3,c4,c5,c6,c7;
not g1(c1,a);
and g2(c2,a,b);
or g3(c3,a,b);
nand g4(c4,a,b);
nor g5(c5,a,b);
xor g6(c6,a,b);
xnor g7(c7,a,b);
endmodule
Program for logic gates and verify its truth table in quartus using Verilog programming

Developed by:J .SRI SARAN RegisterNumber:25015592

Logic symbol & Truthtable de2 RTL realization 
Output: 
<img width="732" height="812" alt="Screenshot 2025-12-27 131023" src="https://github.com/user-attachments/assets/6d9662ba-5862-4387-a8e2-790aaa09b7e9" />
<img width="1107" height="630" alt="Screenshot 2025-12-27 131038" src="https://github.com/user-attachments/assets/78a3a198-da8a-4816-81a0-b68cbd0c15be" />
<img width="1038" height="499" alt="Screenshot 2025-12-27 131101" src="https://github.com/user-attachments/assets/9dd42f33-35ed-41f2-8a93-cdf7214c4c40" />
RESULT;
The basic logic gates are studied and the truth tables are verified.


