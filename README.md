## DATE :   
# EXPERIMENT NO:3 HALF_ADDER_SUBTRACTOR


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



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Developed by: ARCHANA.T

RegisterNumber:212223240013

### HALF ADDER

![image](https://github.com/ARCHANAT1305/HALF_ADDER_SUBTRACTOR/assets/145975189/d9433c5a-8668-4c0f-a450-4ca387e42f11)


**RTL Schematic**
![DG halfadder](https://github.com/ARCHANAT1305/HALF_ADDER_SUBTRACTOR/assets/145975189/ec4fac1a-3a89-4079-947e-a8b6fa38d175)


## Truthtable

![image](https://github.com/ARCHANAT1305/HALF_ADDER_SUBTRACTOR/assets/145975189/3ab6c0f5-6c39-4be1-9474-6a45e96f431b)


**Output/TIMING Waveform**
![DG halfadder wave form](https://github.com/ARCHANAT1305/HALF_ADDER_SUBTRACTOR/assets/145975189/4ed70452-31ee-40a1-8c6e-a587526f7b2e)


### HALF SUBRACTOR

![image](https://github.com/ARCHANAT1305/HALF_ADDER_SUBTRACTOR/assets/145975189/5f91b441-7a61-4799-bd43-cec9fcba439f)

**RTL Schematic**

![image](https://github.com/ARCHANAT1305/HALF_ADDER_SUBTRACTOR/assets/145975189/da8a754b-0dfb-4e3f-83f4-51f2ce7ac725)

## Truthtable

![image](https://github.com/ARCHANAT1305/HALF_ADDER_SUBTRACTOR/assets/145975189/252d1053-0433-495c-a691-0bceaf056f0e)

**Output/TIMING Waveform**

![image](https://github.com/ARCHANAT1305/HALF_ADDER_SUBTRACTOR/assets/145975189/d5cc46dc-0bc0-457f-9fb7-5d2e28d8eda3)


**Result:**  
Thus the program executed successfully.
