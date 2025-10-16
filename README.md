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



**Figure -1 FULL ADDER**

![WhatsApp Image 2025-10-15 at 10 06 01_2a16e69e](https://github.com/user-attachments/assets/289e4179-dff1-4ed1-bb86-19872c26a854)

**Full Subtractor**
![WhatsApp Image 2025-10-15 at 10 05 57_7e5aa7cb](https://github.com/user-attachments/assets/d173739c-c2cd-4609-a7ac-6a7364e0eb41)


A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.



Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**
<img width="1905" height="894" alt="Screenshot 2025-10-16 084416" src="https://github.com/user-attachments/assets/27ab8997-53d5-4c67-9e52-04acf27167f7" />
<img width="1915" height="660" alt="Screenshot 2025-10-16 084654" src="https://github.com/user-attachments/assets/895cad11-233a-4573-b6c8-2a2853e3ddab" />


/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by:G.SHAWN RONEL RegisterNumber:25005544
*/

**RTL Schematic**

**Output Timing Waveform**
![WhatsApp Image 2025-10-15 at 10 05 55_b9c20cce](https://github.com/user-attachments/assets/925f8bcc-e4c1-4742-9c67-21c9eac7a771)
![WhatsApp Image 2025-10-15 at 10 05 56_566a7f0b](https://github.com/user-attachments/assets/55873e58-49d0-426b-b8e8-84ed98eea6f4)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



