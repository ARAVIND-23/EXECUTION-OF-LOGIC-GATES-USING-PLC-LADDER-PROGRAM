# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME :ARAVIND G
 # REGISTER NUMBER :212223240011
 # DEPARTMENT : AIML
 # YEAR : 2nd YEAR

 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.


# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

# Basic Logic Gates:
AND Gate:

Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.
OR Gate:

Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.
NOT Gate:

Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.
NAND Gate:

Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.
NOR Gate:

Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.
XOR Gate:

Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.
# Truth Tables:
![image](https://github.com/user-attachments/assets/650f3519-dbb8-4a60-b80f-45e643039ccb)
![image](https://github.com/user-attachments/assets/5383264b-ddbf-47a9-a3c8-f3255a3f53b3)
![image](https://github.com/user-attachments/assets/cc8dd963-83fb-46ae-b9a4-a67a13d1bf3b)
![image](https://github.com/user-attachments/assets/cb7fc66a-1515-4ba9-9ed1-20d343d116e6)
![image](https://github.com/user-attachments/assets/fb082fc9-8c9b-408f-8032-b387d0d07863)
![image](https://github.com/user-attachments/assets/de39d795-0f0b-4a35-a6df-307c9b9c5f91)

# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS 
![9b53ec74-b4a6-45b5-bfdf-7c578c70dcc0](https://github.com/user-attachments/assets/d38dab73-50be-4817-b037-060de9c01607)
![011538dc-d0cc-469f-aac8-5ed1f849a5d6](https://github.com/user-attachments/assets/81422049-35ad-47e2-a4e9-927d915a63ef)
![ab01cdf2-e77d-4f47-b930-6e0a2fd35a80](https://github.com/user-attachments/assets/56be5f36-0792-4b4a-8b53-d5a08b0620ef)
![IIOT MOODEL](https://github.com/user-attachments/assets/a1de6dcd-89d9-4b7a-94d2-b6b7d6bb3986)
![Screenshot 2024-08-23 083904](https://github.com/user-attachments/assets/ffe778f9-8303-4668-9c40-e03bff5e3216)



#Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
