SOC Design and OpenLane
-----------------------------------------------------------
ASIC design
-------------
![image](https://github.com/user-attachments/assets/61403ae8-2cd5-4ebc-a0e6-abadfae676c1)

What is PDK?

PDK stands for Process Design Kit 
Collection of files used to modal a fabrication process for the EDA tools used to design an IC ;
Process Design Rules: DRC,LVS,PEX

OPEN SOURCE DIGITAL ASIC DESIGN
----------------------------------------
![image](https://github.com/user-attachments/assets/b3459d41-6d82-4ca0-ae92-1d0df95a592d)

EDA TOOLS 

![image](https://github.com/user-attachments/assets/780a31df-7d45-4c0b-9553-a1fc955032da)

ASIC DESIGN FLOW
--------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/5608253d-dd07-43c0-a735-5c42315dcdfa)

Synthesis:
----------
Converts RTL to a circuit out of components from the standard cell library
![image](https://github.com/user-attachments/assets/0058cbd9-c19e-47db-93d4-62ee9318d9b8)

Floor and Power Planning: 
-------------------------
Partition the chip die between differnt system building blocks and place input output Pads 

for macroflooring there will be Dimensions ,PinLocations and Rows

![image](https://github.com/user-attachments/assets/ee0cbbf1-9dae-4466-81cb-5fb3e7022fdc)

Power Planning:
-------------
Power Networks are construcetd in terms of multiple vdd and grounds ,these are connected to all components verticall or horizantal, these are having less resistance due to these are metal surfaces
![image](https://github.com/user-attachments/assets/316123f5-a19c-4817-95f3-47f47b723a96)

Placement:
---------
![image](https://github.com/user-attachments/assets/bd510375-1d2b-4c54-96c2-07a18fa7af9a)

these are two kinds :
global:
optimum position for all cells

detailed: the positions that are obtained from global placemnt are minimally altered
![image](https://github.com/user-attachments/assets/3f379845-acba-457e-82f9-f4ac2a5c4d13)

Clock Tree Synthesis:
----------------------
![image](https://github.com/user-attachments/assets/5276c0c3-18b9-4c49-9283-e52e47b9b0e4)

Routing:
----------
![image](https://github.com/user-attachments/assets/c6b38024-af44-4c76-ae63-d4dad6b71d2f)
![image](https://github.com/user-attachments/assets/05e77ac9-a221-41d1-8a4d-14e206a572f4)

Sign-Off:
--------------
![image](https://github.com/user-attachments/assets/275975d4-411f-4196-968f-0beed460a169)

Introduction to OpenLane ASIC design Flow 
---------------------------------------------------------
![image](https://github.com/user-attachments/assets/400212be-debb-4384-98c0-cdafb4a9e878)

Fault:



