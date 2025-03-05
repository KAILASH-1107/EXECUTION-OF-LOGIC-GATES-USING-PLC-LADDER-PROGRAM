## EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME : V.KAILASH
 # REGISTER NUMBER : 212224240067
 # DEPARTMENT : B.Tech Artificial Intelligence and Machine Learning
 # YEAR : I

 
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

![Screenshot 2025-03-05 201009](https://github.com/user-attachments/assets/a075bbb1-467d-4b99-b17e-16a9717c9034)


![Screenshot 2025-03-05 201025](https://github.com/user-attachments/assets/796f5d4d-bc45-4fea-a1af-952c0e79bb1f)


![Screenshot 2025-03-05 201040](https://github.com/user-attachments/assets/bc4b6b6f-a1b2-478f-841e-f576bdcc842e)


![Screenshot 2025-03-05 201054](https://github.com/user-attachments/assets/6a25b71d-589c-4c42-bcbf-253d07b35c75)


![Screenshot 2025-03-05 201649](https://github.com/user-attachments/assets/f32bdc23-8b81-4250-93fa-90e02d51ac2e)


![Screenshot 2025-03-05 201731](https://github.com/user-attachments/assets/6ac2a262-1968-4298-b966-80aff564f9c2)



![Screenshot 2025-03-05 201752](https://github.com/user-attachments/assets/d40045fd-65b1-4d8a-9865-4a5d44cc802e)



![Screenshot 2025-03-05 201801](https://github.com/user-attachments/assets/2dc85715-072f-4554-a1b4-5e14fbfe59bd)



![Screenshot 2025-03-05 201953](https://github.com/user-attachments/assets/7e75f063-f0ef-4662-8401-0ce088726ee0)


![Screenshot 2025-03-05 202005](https://github.com/user-attachments/assets/9364ec7e-d7a1-41d0-a7e1-88dcbaacd041)



![Screenshot 2025-03-05 202015](https://github.com/user-attachments/assets/ac62d097-2524-4adc-b892-c0a853f3e877)



![Screenshot 2025-03-05 202026](https://github.com/user-attachments/assets/6ad60164-4f10-4726-b862-df1ede71ff33)


![Screenshot 2025-03-05 202208](https://github.com/user-attachments/assets/65914e02-ca75-482a-b192-b301665788b0)


![Screenshot 2025-03-05 202217](https://github.com/user-attachments/assets/85f078bf-b16e-4f36-9424-a55e91677e27)


![Screenshot 2025-03-05 202227](https://github.com/user-attachments/assets/e55f2bba-d435-4f32-afc1-7ff1386f20e9)



![Screenshot 2025-03-05 202236](https://github.com/user-attachments/assets/bd28007d-ddbf-4326-aa9a-5ed39df09ed0)



![Screenshot 2025-03-05 202504](https://github.com/user-attachments/assets/b01bf2a6-ff0c-4d64-8c77-8f284165ede1)



![Screenshot 2025-03-05 202517](https://github.com/user-attachments/assets/8d498bff-fe52-4ff5-8dd1-d8ad4c48cde4)



![Screenshot 2025-03-05 202528](https://github.com/user-attachments/assets/82d9fa1e-09cc-44a5-b85f-1bac8e48bee8)





![Screenshot 2025-03-05 202537](https://github.com/user-attachments/assets/96265172-c9e1-4e62-b8b1-7beef3e8c7e4)


















# Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
