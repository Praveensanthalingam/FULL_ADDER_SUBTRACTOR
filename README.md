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
FULL ADDER

![image](https://github.com/user-attachments/assets/9fe3ad3b-0efc-4d7d-8fc5-6f26e1174c8c)

FULL SUBTRACTOR

![image](https://github.com/user-attachments/assets/04af1e42-91b1-49f9-8635-7a6af5c39d8b)



**Procedure**

Write the detailed procedure here

**Program:**

FULL ADDER

![Screenshot 2024-12-08 213739](https://github.com/user-attachments/assets/a1ba7db3-c8f4-48af-aefa-601def045936)

FULL SUBTRACTOR

![Screenshot 2024-12-08 214101](https://github.com/user-attachments/assets/49449ccb-0411-46f4-945c-e76b48a65f4b)


/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**
FULL ADDER
![Screenshot 2024-12-08 215153](https://github.com/user-attachments/assets/88fda2d0-db6d-43ba-a1b7-0aa93133a558)

FULL SUBTRACTOR
![Screenshot 2024-12-08 215231](https://github.com/user-attachments/assets/94f7a15c-bab3-428b-8196-13ceab491913)

**Output Timing Waveform**

FULL ADDER
![Screenshot 2024-12-08 214453](https://github.com/user-attachments/assets/7cd72255-52ac-4e7c-8799-289bb224403d)

FULL SUBTRACTOR
![Screenshot 2024-12-08 214816](https://github.com/user-attachments/assets/0b1f8eb5-5aaf-43c2-85e2-cbfe6bc116c5)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



