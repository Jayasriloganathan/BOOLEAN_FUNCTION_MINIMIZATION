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
``` 
module ha_dataflow(a, b, s, ca); 
    input a; 
    input b; 
    output s; 
    output ca; 
  assign#2 s=a^b; 
  assign#2 ca=a&b;
  endmodule
```

Developed by:Jayasri L
RegisterNumber:24900407
/*


**RTL realization**

![Screenshot 2024-12-10 122101](https://github.com/user-attachments/assets/5f6483f1-ab6d-4ce5-9e4c-f372ed70635

**Timing Diagram**

![Screenshot 2024-12-10 122124](https://github.com/user-attachments/assets/911516d5-91e2-4a4c-b93d-94ccb19bc7aa)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

