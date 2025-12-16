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

Developed by:samrin.T RegisterNumber:25012955
  i) 
    module exp2(a,b,c,d,f1); 
    input a,b,c,d; 
    output f1; 
    assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
    endmodule 
  ii) 
    module exp3(w,x,y,z,f2); 
    input w,x,y,z; 
    output f2; 
    assign f2=((~y & z)|( w & y )|(x & y)); 
    endmodule

**RTL realization**
<img width="1037" height="566" alt="Screenshot 2025-12-16 215615" src="https://github.com/user-attachments/assets/34413517-3b3f-49e2-99e5-2268600b8dd5" />
<img width="1038" height="577" alt="Screenshot 2025-12-16 215706" src="https://github.com/user-attachments/assets/5c5469fe-261e-44cb-8c12-e341111b2aaf" />


**Output:**
<img width="1038" height="568" alt="Screenshot 2025-12-16 215818" src="https://github.com/user-attachments/assets/da57e2d2-00c6-4c68-8c3d-d46836433312" />
<img width="1045" height="573" alt="Screenshot 2025-12-16 220004" src="https://github.com/user-attachments/assets/9ab4147e-2a00-4639-b2e9-64f38083352e" />

**RTL**
<img width="1038" height="571" alt="Screenshot 2025-12-16 220045" src="https://github.com/user-attachments/assets/962a1291-6f44-4fd4-ad16-2f79e42fb2b0" />
<img width="1035" height="569" alt="Screenshot 2025-12-16 220117" src="https://github.com/user-attachments/assets/9efb4fc6-88b1-467e-8909-7e67b8909e24" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

