We have the placement and routed version of the chip .If we pick up the cells over the chip ,these cells are called Standard Cells.
These Standard Cells are placed in Library

![Screenshot 2024-10-08 151247](https://github.com/user-attachments/assets/63773f7e-7c1e-4a71-ad1c-723314934253)

![Screenshot 2024-10-08 152139](https://github.com/user-attachments/assets/b2875f55-1b97-4c45-bff8-b15f8dbb6d4a)

Library has different gates with different functionality but also got different cells with different sizes.These are the physical characterization of the cells

![Screenshot 2024-10-08 152205](https://github.com/user-attachments/assets/c239416c-d64e-4b17-8aae-3dea4e15522c)
If we take a particular cell lets take an inverter it has different threshold voltages and take more time to .

Cell Design Flow
---
Cells design flow has three steps 

![Screenshot 2024-10-08 152220](https://github.com/user-attachments/assets/62b5ead3-5e95-414a-a2e9-760eb07857ac)

Inputs:
--
Foundary provides PDKS it consists of DRC AND LVS rules and Spice models 

![Screenshot 2024-10-08 152245](https://github.com/user-attachments/assets/0c241abc-9fa5-472f-9560-84dbf15cd642)
![Screenshot 2024-10-08 152307](https://github.com/user-attachments/assets/e8be5bec-5708-48de-9e94-692ebbc1feea)

Library and User designer Specs :

Design Step :
--
i)Circuit-Design:

Using the input we will design cells
It has two steps :
i)Implement the functionality of the cell
ii)modal the pmos and cmos transistor based on requriments 


ii) Layout -Design:
 1) In layout Design,we do implementation of function using pmos and nmos 

 2) To derive the pmos and n mos graph using EULIER'S PATH

Eulier's Path:
The path that is traced only once

The next step is Draw the stick Diagram ,based on the circuit we connect the stick diagram



Characterization Flow:
--
We have layout of the buffer and two inverters connected back to back along with pulses and spice netlist

It has sub circuit model in which actual pmos and n mos specifications are present.In sub circuits we have spice models.

Charachterization flow:
 1) Reading the models and tech files
 2) Read the extracted spice netlist
 3) Define or recognize the behaviour of buffer
 4) read the sub circuits of inverter
 5) Attach the necessary power supply
 6) Applying the stimulus
 7) Necessary putput capacitors
 8) Necessary simulation commands

These steps are feed in characterization software called GUNA and we generate Timing noise ,Power.libs etc.,
