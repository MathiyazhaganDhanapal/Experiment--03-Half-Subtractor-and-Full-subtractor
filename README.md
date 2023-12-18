## Name:D.MATHIYAZHAGAN.
## Reg:23013685

## Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure


Write the detailed procedure here 


## Program:

## Half subractor:

![WhatsApp Image 2023-12-18 at 15 28 32_00ab4800](https://github.com/vasanthkumarch/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145981115/b537d910-b7de-4fe7-8c76-1fae57900b44)

## Full subractor:
![WhatsApp Image 2023-12-18 at 15 28 32_3726459e](https://github.com/vasanthkumarch/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145981115/4767d6b2-74ff-4be1-bb66-6872cf4432a0)



Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: 

## RTL REALIZATION:

## Half subractor:

![291159722-c4b05717-c38c-402f-ae56-aab9da4e65d1](https://github.com/vasanthkumarch/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145981115/cefb5b45-7bb7-4fd4-a7ff-a7223de61058)

## Full subractor:
![c634113c-b4f9-45a3-8d45-c533891d187e](https://github.com/vasanthkumarch/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145981115/bb5b76bb-2e72-4f3a-8ee4-324f812cc739)


## Timing diagram:

## Half subractor:
![286511423-7b10a3ee-8c3b-49a4-88c2-95059ef32a3e](https://github.com/vasanthkumarch/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145981115/ce16f779-5eb5-4fef-a370-1bb4adaefd3e)


## Full subractor:
![ea854b7e-45bd-4699-8d4f-06b431c3dd53](https://github.com/vasanthkumarch/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145981115/5111567c-95ae-49f0-98bc-7d5cdd26b9b6)


## Truthtable:

## Half subractor:
![286511396-8e10cf55-5b1a-4089-b750-49f6acdad175](https://github.com/vasanthkumarch/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145981115/8fc06485-2133-4ec8-ae0b-db61963710c9)


## Full subractor:
![dd4f6c7b-177e-4325-b279-4b661ec0b734](https://github.com/vasanthkumarch/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145981115/1fbdc22e-1c35-4e91-a8e8-d72932139c65)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
