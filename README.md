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
```
Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: JINITH KUMAR V RegisterNumber: 212225040157
```
```
module boolean_function(
    input A,B,C,D,
    output F
);
assign F = (~a&~b&~c&~d) | (a&~c&~d) |(~b&c&~d) |(~a&b&c&d) | (b&~c&d);
endmodule
```

**RTL realization**
![alt text](<WhatsApp Image 2026-03-14 at 10.31.41 AM (1).jpeg>)
**Output:**

**RTL**

![alt text](<WhatsApp Image 2026-03-14 at 10.31.41 AM (2).jpeg>)
**Timing Diagram** 
![alt text](<WhatsApp Image 2026-03-14 at 10.31.41 AM.jpeg>)
**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

