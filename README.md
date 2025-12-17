# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/*
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

*/
Developed by: Rishikesh S

RegisterNumber: 25005617


**RTL realization**
F1
<img width="737" height="357" alt="EX 2 LOGIC 1" src="https://github.com/user-attachments/assets/69739426-f970-42f5-ae17-84c45b400516" />

F2
<img width="709" height="381" alt="EX 2 LOGIC 2" src="https://github.com/user-attachments/assets/6b67c7c2-75cc-4f9e-8da4-cc8b251f9335" />


**Output:**
F1
<img width="959" height="565" alt="EX 2 WAVE 1" src="https://github.com/user-attachments/assets/9d5fd03e-8391-4a50-8f47-5fb7f2ad3379" />

F2
<img width="960" height="564" alt="EX 2 WAVE 2" src="https://github.com/user-attachments/assets/9fde6ea9-0a18-43b6-8a31-a5d30686a602" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

