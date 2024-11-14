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
![386122056-c1f6c943-f462-4582-8ebd-e945a82ae6d5](https://github.com/user-attachments/assets/d89f7d0e-4d68-4aaf-979b-b932ea28c149)

**Procedure**

Write the detailed procedure here
1 Type the program in Quartus software.
2 Compile and run the program.
3 Generate the RTL schematic and save the logic diagram.
4 Create nodes for inputs and outputs to generate the timing diagram.
5 For different input combinations generate the timing diagram.
**Program:**
![386124031-bc6f2a95-f944-4fcb-94fa-c3fd379c4cec](https://github.com/user-attachments/assets/6805372b-8809-43f9-a60f-2dc4d0fe9440)

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/24007963

**RTL Schematic**
![386124137-191879b2-465c-4e71-9046-0ddc00ef6217](https://github.com/user-attachments/assets/9128119f-a637-45bb-ac49-0221a5af2333)

**Output Timing Waveform**
![386124340-084240df-435a-4f27-9460-eb33ccf4fe6d](https://github.com/user-attachments/assets/338fa9c5-a45c-4f83-a920-09d62d3af4c7)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



