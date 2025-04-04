# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**
![OUTPUT](<ex de2.jpg>)
![OUTPUT](<EX DE2(i).jpg>)
![OUTPUT](<EX DE2(3).jpg>)
![OUTPUT](<EX DE(4).jpg>)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
Developed by:Megha S
Date :12/03/2025
RegisterNumber: 212224230157
```
```
First program:
module EXP2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d|a&b&~c|~a&b&d));
endmodule

Second program:
module EXP2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z|x&y|w&y));
endmodule

```


**RTL realization**
![output](<DE EX2-1.png>)
![output](<DE EX2-1(2).png>)

**Output:**

**RTL**

**Timing Diagram**
![OUTPUT](<DE EX2-2.png>)
![OUTPUT](<DE EX2-2(2).png>)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

