## NAME: JAYAPRADAN M

## REG NO: 24900886 

##   EXPERIENMENT NO 4: IMPLEMENTATION OF FULL ADDER AND SUBTRACTOR

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

**TRUTH TABLE**
## FULL ADDER:
![WhatsApp Image 2024-12-26 at 11 04 14_a6018e38](https://github.com/user-attachments/assets/c8493ea4-fe91-4d51-b6c7-712922817a95)
## FULL SUBRACTOR:

![WhatsApp Image 2024-12-26 at 11 04 14_6d7b1a39](https://github.com/user-attachments/assets/eed9687f-4ef8-4b4a-af5d-ea946121b47d)


**PROGRAMN:**

![WhatsApp Image 2024-12-26 at 11 04 14_218a27ba](https://github.com/user-attachments/assets/72a7f09d-69c8-458a-9fc1-4986e37a0cb6)


## RTL VIEWER 

![WhatsApp Image 2024-12-26 at 11 04 13_0fb9965f](https://github.com/user-attachments/assets/786a1772-d7f4-48c0-8b92-83d8abff0019)

## OUTPUT TIMING WAVEFORM:

![WhatsApp Image 2024-12-26 at 11 04 13_1d6e37e7](https://github.com/user-attachments/assets/d0b1b2dd-ac26-4f0d-9565-db8331842396)

**RESULT:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified in Quartus software using verilog program successfully
