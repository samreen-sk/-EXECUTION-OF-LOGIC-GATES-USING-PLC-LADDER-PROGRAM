# EX 1 : EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME : Pavithra P
 # REGISTER NUMBER : 212223110035
 # DEPARTMENT:CSE(IOT)
 # YEAR : 3rd

 
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
## AND 
<img width="239" height="237" alt="image" src="https://github.com/user-attachments/assets/4320974e-1918-4e38-8ae9-40164f604eef" />

## OR
<img width="233" height="232" alt="image" src="https://github.com/user-attachments/assets/df0044b0-2ec6-4f53-b0ef-807d3e6c79f6" />

## NOT
<img width="234" height="159" alt="image" src="https://github.com/user-attachments/assets/5f5b3d34-d10a-4cb2-98b7-0d243f523cda" />

## NAND 
<img width="234" height="234" alt="image" src="https://github.com/user-attachments/assets/d6cac8ee-3379-41c0-9a7a-4fea69928562" />

## NOR
<img width="239" height="238" alt="image" src="https://github.com/user-attachments/assets/bcf4f349-bc2c-4a83-9b21-15f34a895375" />

## XOR
<img width="264" height="237" alt="image" src="https://github.com/user-attachments/assets/f7e3e0cd-88ad-4bc0-af7a-46b1ce453003" />

## XNOR
<img width="235" height="237" alt="image" src="https://github.com/user-attachments/assets/8c5ad738-5242-4460-aa1f-a4745c0898a9" />








 
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
## AND GATE & OR GATE :
<img width="758" height="333" alt="Screenshot 2025-09-11 172914" src="https://github.com/user-attachments/assets/7b04c59a-11e9-4bad-b6e1-437a13aeab6d" />
<img width="703" height="343" alt="Screenshot 2025-09-11 172927" src="https://github.com/user-attachments/assets/46966762-24db-4707-82a0-1b240e3ce9e3" />
<img width="689" height="344" alt="Screenshot 2025-09-11 172939" src="https://github.com/user-attachments/assets/975d3c6c-bb57-4a18-ab53-7c5131250305" />
<img width="723" height="338" alt="Screenshot 2025-09-11 172950" src="https://github.com/user-attachments/assets/6b51e8fe-942e-4f5e-b831-d8c26d26072b" />

## NOT GATE:
<img width="685" height="139" alt="Screenshot 2025-09-11 172959" src="https://github.com/user-attachments/assets/5efcf254-bb17-4a7d-8277-994fb06ecbf1" />
<img width="658" height="126" alt="Screenshot 2025-09-11 173013" src="https://github.com/user-attachments/assets/eaf4fbd9-9698-4ed8-8b2d-ea64b448d89c" />

## NAND GATE:

<img width="650" height="264" alt="Screenshot 2025-09-11 173042" src="https://github.com/user-attachments/assets/5d94643f-05e8-4f96-b33f-1cb144f61ff5" />
<img width="644" height="264" alt="Screenshot 2025-09-11 173053" src="https://github.com/user-attachments/assets/20f75a17-e7f3-48d4-b442-d8d78cc0e12b" />
<img width="650" height="268" alt="Screenshot 2025-09-11 173106" src="https://github.com/user-attachments/assets/fc6cadb8-7e6f-45c5-ab73-252c3e2541c8" />
<img width="674" height="275" alt="Screenshot 2025-09-11 173129" src="https://github.com/user-attachments/assets/7d2f8a61-3952-4454-87f5-9f1f29b7914f" />

## NOR GATE:
<img width="660" height="347" alt="Screenshot 2025-09-11 173213" src="https://github.com/user-attachments/assets/57785775-ad6c-4672-a862-5c312b57177a" />
<img width="551" height="338" alt="Screenshot 2025-09-11 173232" src="https://github.com/user-attachments/assets/beb4aeeb-b0c6-4048-9c3b-fc1a84cc7d04" />
<img width="623" height="335" alt="Screenshot 2025-09-11 173250" src="https://github.com/user-attachments/assets/2c75a220-54a0-452d-8791-a2e21fba3f4c" />
<img width="591" height="341" alt="Screenshot 2025-09-11 173315" src="https://github.com/user-attachments/assets/d41511bc-4299-48d1-b55b-a60fe7511e34" />

## XOR & XNOR GATES :
<img width="670" height="419" alt="Screenshot 2025-09-11 173353" src="https://github.com/user-attachments/assets/bbeddf96-cd4b-48b7-9bc8-3fe9c85f5fb9" />
<img width="670" height="425" alt="Screenshot 2025-09-11 173406" src="https://github.com/user-attachments/assets/bb5bfad7-0820-4a3e-a478-c9a38e89a8fd" />
<img width="643" height="413" alt="Screenshot 2025-09-11 173418" src="https://github.com/user-attachments/assets/744e488b-9459-4308-a8c9-1305f13be85f" />
<img width="696" height="424" alt="Screenshot 2025-09-11 175131" src="https://github.com/user-attachments/assets/f0682e71-c69e-4309-9012-ef99ca5ff12d" />






















## Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
