Implementation-of-Full-Adder-and-Full-subtractor-circuit

AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

Equipments Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

Full Adder and Full Subtractor

Full Adder

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin

Carry = AB + ACin + BCin

![full adder](https://github.com/Kalyanesree/exp3/assets/163311552/726a5712-a62b-4b49-aa54-a38d9ca7d1d5)

Figure -1 FULL ADDER

Full Subtractor

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![full subtractor](https://github.com/Kalyanesree/exp3/assets/163311552/2009147a-9589-4234-9045-5fef08e9054f)


Truthtable

FULL ADDER
![adder table](https://github.com/Kalyanesree/exp3/assets/163311552/114f9122-319d-4db0-9bf1-854b4bdcdbc7)

FULL SUBTRACTOR
![subtractor table](https://github.com/Kalyanesree/exp3/assets/163311552/1a824f88-12a6-4b7d-8f2f-6341d018836c)



Procedure

Write the detailed procedure here

Program:

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
FULL ADDER
![adder program](https://github.com/Kalyanesree/exp3/assets/163311552/eb05f4f2-932e-4696-8832-f57fd7215168)

FULL SUBTRACTOR
![subtractor program](https://github.com/Kalyanesree/exp3/assets/163311552/0454dd1e-e6d6-40cd-a5f5-b0dcd17948a6)


Developed by: KALYANE SREE M                RegisterNumber: 212222050028

RTL Schematic
FULL ADDER 
![adder diagram](https://github.com/Kalyanesree/exp3/assets/163311552/7a411565-e231-44ca-90e2-e933cf7b5acc)

FULL SUBTRACTOR
![subtractor diagram](https://github.com/Kalyanesree/exp3/assets/163311552/8abcdc36-445d-4730-aca3-b854f4a4286e)



Output Timing Waveform

![waveform](https://github.com/Kalyanesree/exp3/assets/163311552/aecb08ef-0645-4f36-9057-dc543e28a6f1)


Result:

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software
