# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**


![WhatsApp Image 2024-12-03 at 11 20 56_30e77f59](https://github.com/user-attachments/assets/30c4bd41-3e44-44d6-975b-5e717001ae85)
![WhatsApp Image 2024-12-03 at 11 25 08_b9b4c91e](https://github.com/user-attachments/assets/ffb2cb0b-4d0b-4433-b5d0-14e8b6d3c939)



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:Thamizh.S RegisterNumber:24900483*/

![adder code (2)](https://github.com/user-attachments/assets/324f13cf-e611-4f7a-9b9b-8c6cb9adfd1e)

![Screenshot 2024-12-03 111100](https://github.com/user-attachments/assets/edba0857-260a-4d47-9911-1b7f8507ce38)

**RTL ![Uploading Screenshot 2024-12-03 111100.png…]()
Schematic**

![adder logic](https://github.com/user-attachments/assets/8308c81f-ae11-4d75-b594-17f8814eabd9)

![Screenshot 2024-12-03 111115](https://github.com/user-attachments/assets/55e6bffb-50de-417e-8ecc-980a5eb0eb1b)

**Output/TIMING Waveform**

![adder wave](https://github.com/user-attachments/assets/0790066d-ba28-45f4-ab0b-14efccdcf807)

![Screenshot 2024-12-03 111042](https://github.com/user-attachments/assets/1d644331-15bf-456b-ab40-b0057d58e537)


**Result:**
