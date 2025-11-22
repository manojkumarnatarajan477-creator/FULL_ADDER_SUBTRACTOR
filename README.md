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

**Procedure**

Write the detailed procedure here

**Program:**

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:


**RTL Schematic**

**Output Timing Waveform**

**Result:**
FULL ADDER:
<img width="1919" height="1079" alt="RTL VIEWER EX3 I" src="https://github.com/user-attachments/assets/911c819d-24cd-4c15-94fe-953ef3a164ed" />
<img width="1919" height="1079" alt="WAVEFORM EX3 I" src="https://github.com/user-attachments/assets/935a3b6b-dd1d-4881-a73d-72e9c8ea9ab9" />

FULL SUBRACTOR:
<img width="1919" height="1079" alt="RTL VIEWER EX3 II" src="https://github.com/user-attachments/assets/95015e4e-65b8-4505-8967-168812639c98" />
<img width="1916" height="1079" alt="WAVEFORM EX3 II" src="https://github.com/user-attachments/assets/b93324b9-1f2f-4e6e-bdf5-8e55048ab8fd" />











Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



