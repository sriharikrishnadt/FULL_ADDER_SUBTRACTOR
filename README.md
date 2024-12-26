## NAME : SRI HARI KRISHNA D T
## REG NO : 24900669
## EX 4 :FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

## AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

## EQUIPMENTS REQUIRED:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

## FULL ADDER AND SUBRACTER:

## FULL ADDER

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

## FIGURE 1 FULL ADDER:

## FULL SUBRACTER

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

## TRUTH TABLE:
## FULL ADDER
![image](https://github.com/user-attachments/assets/1169c653-ca25-4d8b-87bd-95288fb0241e)

## FULL SUBRACTER
![image](https://github.com/user-attachments/assets/2929ea90-6432-4256-afb1-339f1fee3362)



## PROCEDURE
## Full Adder
1.Open Quartus II and create a new project.
2.Use schematic design entry to draw the full adder circuit.
3.The circuit consists of XOR, AND, and OR gates.
4.Compile the design, verify its functionality through simulation.
5.Implement the design on the target device and program it.
## Full Subtractor
1.Follow the same steps as for the full adder.
2.Draw the full subtractor circuit using schematic design.
3.The circuit includes XOR, AND, OR gates to perform subtraction.
4.Compile, simulate, implement, and program the design similarly to the full adder.


## PROGRAM:

![image](https://github.com/user-attachments/assets/3dcfe49b-cc10-45dc-b6fc-18fd64efe6b7)

## RTL VEIWER:
![image](https://github.com/user-attachments/assets/1a2bb04d-51cc-4490-8a00-e8c68b6e55a4)


## OUTPUT TIMING WAVEFORM:
![image](https://github.com/user-attachments/assets/cb5afa35-6eef-4077-8a79-59c9ef656563)


## RESULT:

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified in Quartus software
using verilog program.




