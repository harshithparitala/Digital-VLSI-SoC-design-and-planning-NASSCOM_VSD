This following file contains the Lab sections on chip floor planning considerations and it has three sections 

Step to Floor Planning using Open lane 
Review floor plan files and steps to view floorplan
Review floorplan layout in Magic
---------------------------------
Let's move to OpenLANE and understand the concepts of floorplanning and automatic place and route.

After a summary of day 1 and flop rate calculations, we will take a closer look at the concepts of floorplanning, placement and routing.

For running the floorplan 

cd: % run_floorplan
-------
After that we will get various varibles corresponds to synthesis flow, floorplanning eyc.,

![Screenshot from 2024-10-06 00-10-07](https://github.com/user-attachments/assets/b9097495-07bb-45e2-a87c-7fd02810ebe9)
chip
Floorplanning: 
--
In this we observed core utilization , Aspect ratio etc.,

![Screenshot from 2024-10-06 00-10-37](https://github.com/user-attachments/assets/1009d6d8-cefc-4059-b428-0bd3b5f95faa)

placement
--------
![Screenshot from 2024-10-06 00-11-50](https://github.com/user-attachments/assets/d4462b44-2d20-472e-ab84-3f7114c9b9ac)

![Screenshot from 2024-10-06 00-13-26](https://github.com/user-attachments/assets/f614ec3f-603c-4623-855a-f6dd210db706)

DESIGN :
---
![Screenshot from 2024-10-06 00-14-33](https://github.com/user-attachments/assets/8ccb49dc-c521-4d35-b564-41b15c724288)

Diearea : it gives the dimension of the core 

![Screenshot from 2024-10-06 00-29-03](https://github.com/user-attachments/assets/14731503-9a11-4297-9f4c-5587197f261b)

Opening the Layout we use Magic tool , following cd will dirct to the Magic tool

cd
--
:magic -T /home/vsduser/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech led read ../../tmp/merged.lef def read picorv32a.floorplan.def &

![Screenshot from 2024-10-06 00-45-49](https://github.com/user-attachments/assets/86b08555-3ef3-40dd-963d-651aacf2585a)

Given diagram shows the die of the design and standard cells as well as pre placed cells are shown

![Screenshot from 2024-10-06 00-54-11](https://github.com/user-attachments/assets/d7a5dd05-15ab-4daa-b9f0-929a1dad421c)

we need to select the specific port to know about the details and we need to write what in tkcon.tcl window

![Screenshot from 2024-10-06 01-15-48](https://github.com/user-attachments/assets/bd2a635c-4d81-4737-b4c9-3c8306a1547e)

![Screenshot from 2024-10-06 01-14-17](https://github.com/user-attachments/assets/a8d3ec86-1812-49ed-8302-78e35ec5db12)


