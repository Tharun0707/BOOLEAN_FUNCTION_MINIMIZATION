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

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: THARUN SRIDHAR 
RegisterNumber: 212223230230

```
i)
module exp2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d) | (a & b & ~c) | (~a & b & d));
endmodule

ii)
module ex2m2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2= ((~y&z)|(w&y)|(x&y));
endmodule
```

**LOGIC SYMBOL AND TRUTH TABLE**
![image](https://github.com/user-attachments/assets/22370d1b-17b9-4c79-b5ad-9c9c1422cef6)
![image](https://github.com/user-attachments/assets/01a37c85-5a5d-43cb-a5dd-f9bbe50557e7)



**RTL realization**

i)
![Screenshot (27)](https://github.com/user-attachments/assets/16d2c2c1-bcf7-485b-a59a-39df1e4994ab)

ii)
![Screenshot (28)](https://github.com/user-attachments/assets/25fb10bd-cd9d-4407-995d-11f9b3baf517)


**Output:**

i)
![exp2 ss](https://github.com/user-attachments/assets/fbf70f26-0fbd-4909-85a2-a5b4455f32a1)

ii)
![exp2 2 ss](https://github.com/user-attachments/assets/555b6c30-5a34-459f-acc9-3a0f5be21775)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

