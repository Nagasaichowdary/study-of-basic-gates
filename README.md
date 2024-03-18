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

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by:P.Aditya Naga Sai
 RegisterNumber: 212223110036
 ![Screenshot 2024-03-18 082745](https://github.com/Nagasaichowdary/study-of-basic-gates/assets/155174528/251954aa-1dff-465d-9c65-c959f5cf2910)

**Logic symbol & Truthtable**
![Screenshot 2024-03-18 082812](https://github.com/Nagasaichowdary/study-of-basic-gates/assets/155174528/079bf9f1-4a22-4921-ab81-ff08a6b64967)
**RTL realization Output:** 
![Screenshot 2024-03-18 082829](https://github.com/Nagasaichowdary/study-of-basic-gates/assets/155174528/a8ad7f40-3d57-4a5e-b053-9a2024f4f2b3)

**RTL**
![Screenshot 2024-03-18 082906](https://github.com/Nagasaichowdary/study-of-basic-gates/assets/155174528/29828b3b-0f25-4e59-8bfc-c10f76589f2a)

**Result:**
Thus the truth table of logic gates in Quartus II using Verilog programming are studied, verified and executed successfully.

