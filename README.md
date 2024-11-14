# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
![386181684-4d0ec8e8-61df-4918-86c4-9afe9a1c352f](https://github.com/user-attachments/assets/77c6f5ef-c011-4809-9b68-f3565a014d0f)

**Procedure**

Write the detailed procedure here
1 Type the program in Quartus software.
2 Compile and run the program.
3 Generate the RTL schematic and save the logic diagram.
4 Create nodes for inputs and outputs to generate the timing diagram.
5 For different input combinations generate the timing diagram.
**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/![386124031-bc6f2a95-f944-4fcb-94fa-c3fd379c4cec](https://github.com/user-attachments/assets/cb005718-cab6-44d6-bbb2-fb0c0fe515b7)


**RTL Schematic**
![386124137-191879b2-465c-4e71-9046-0ddc00ef6217](https://github.com/user-attachments/assets/677974ab-923b-40eb-85c7-514aae7bc5d9)

**Output Timing Waveform**
![386124340-084240df-435a-4f27-9460-eb33ccf4fe6d](https://github.com/user-attachments/assets/022a61b1-f493-4faa-8044-a7b2cb36a020)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



