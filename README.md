# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![WhatsApp Image 2024-12-04 at 13 26 01_ca9e86e8](https://github.com/user-attachments/assets/23df1bdb-b719-4b1e-8f83-7409d215d7ca)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Jayasree T s 
RegisterNumber:24900147

```
```
module ex_2(a,b,c,d,w,x,y,z,f1,f2)
intput a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

**RTL realization output**

![WhatsApp Image 2024-12-02 at 18 09 48_965d561d](https://github.com/user-attachments/assets/2bf46519-91c8-404a-a970-fc1ef845d8e0)

**Timing Diagram**

![Screenshot 2024-11-05 204145](https://github.com/user-attachments/assets/75aed6a7-8b97-48fe-b08a-f27a12bae5ec)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

