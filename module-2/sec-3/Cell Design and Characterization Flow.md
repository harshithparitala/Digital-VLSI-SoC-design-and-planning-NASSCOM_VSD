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

![Screenshot 2024-10-08 190908](https://github.com/user-attachments/assets/c33031eb-5784-4365-9a61-9e8a7707c6ad)

![Screenshot 2024-10-08 190929](https://github.com/user-attachments/assets/51ccdad7-dfa5-4756-96d2-197219c02440)

Design Step :
--
i)Circuit-Design:

Using the input we will design cells
It has two steps :
i)Implement the functionality of the cell
ii)modal the pmos and cmos transistor based on requriments 

![Screenshot 2024-10-08 190959](https://github.com/user-attachments/assets/1af80b77-e364-441b-a356-3950bcfe5d39)

ii) Layout -Design:
 1) In layout Design,we do implementation of function using pmos and nmos 

![Screenshot 2024-10-08 191012](https://github.com/user-attachments/assets/def6784f-3ede-466a-aa43-a1cb2913f6c6)

 2) To derive the pmos and n mos graph using EULIER'S PATH

Eulier's Path:
The path that is traced only once

![Screenshot 2024-10-08 191036](https://github.com/user-attachments/assets/a82cb941-091a-4d78-b31a-a424fd63cbfe)

The next step is Draw the stick Diagram ,based on the circuit we connect the stick diagram


![Screenshot 2024-10-08 191047](https://github.com/user-attachments/assets/548816b4-1394-4eea-afd9-b749d7dd724a)

![Screenshot 2024-10-08 191107](https://github.com/user-attachments/assets/7f0959ba-c2a7-41ea-8aab-ded0538b3f9a)

![Screenshot 2024-10-08 191131](https://github.com/user-attachments/assets/2779c00c-6a65-4c99-8090-a731fa70ac62)

Characterization Flow:
--
We have layout of the buffer and two inverters connected back to back along with pulses and spice netlist

![Screenshot 2024-10-08 191220](https://github.com/user-attachments/assets/a62ca7a5-ee45-48ad-a6cd-b0e99d461e8a)

It has sub circuit model in which actual pmos and n mos specifications are present.In sub circuits we have spice models.

![Screenshot 2024-10-08 191245](https://github.com/user-attachments/assets/09c5d033-5bd9-458c-adfe-0365838730a6)

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

![Screenshot 2024-10-08 191300](https://github.com/user-attachments/assets/5d5f3009-c7fb-4aa0-8afa-3d686972f4af)

