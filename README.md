### ENCODER 8TO3 DATAFLOW Modelling

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

**Procedure**

/* write all the steps invloved */

**PROGRAM**

Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming. 

Developed by: ROSHINI A / RegisterNumber: 24002364
![Screenshot 2024-12-17 153822](https://github.com/user-attachments/assets/f31e8c7b-d67d-4def-8a0c-114c48ac6172)


**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**
![Screenshot 2024-12-17 153844](https://github.com/user-attachments/assets/a4e55769-7906-419b-9564-e7fe6d3457d3)

**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**
![Screenshot 2024-12-17 153905](https://github.com/user-attachments/assets/c56ff49f-d688-4fd8-8797-1f4682e0269a)

**RESULTS**
Thus Encoder 8 to 3 designed and truthtable is verified.




