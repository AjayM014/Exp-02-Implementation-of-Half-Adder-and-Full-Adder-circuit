# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:

i)Hald Adder

![image](https://github.com/AjayM014/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150011759/fb3b00e3-ff2f-4ea8-8aa8-e8e810548185)

ii)Full Adder

![image](https://github.com/AjayM014/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150011759/cec0e57b-0171-4531-92d7-54c204c17855)

/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: AJAY M
RegisterNumber:  23013424
*/
Logic symbol & Truthtable

RTL realization


### Output:
### RTL
### TIMING DIAGRAM
i)Half Adder

![image](https://github.com/AjayM014/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150011759/fa51851c-ddc8-4849-a987-3a73014b0422)

ii)Full Adder

![image](https://github.com/AjayM014/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150011759/e5bbe566-42a7-4112-b92a-8836d4f6af87)


### TRUTH TABLE 

i)Half Adder


![image](https://github.com/AjayM014/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150011759/a1a5b658-8f7f-45c8-afb2-36f1914a5893)

ii)Full Adder


![image](https://github.com/AjayM014/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150011759/83800a1d-f526-4edf-8750-3b764eacda6f)

### Result:

To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.
