In thie first lecture of this section . we disscused about somple basic linux comands 

For Example:
------------
cd : Using this command we can move in both ways in the directory tree.

ls : It lists all the sub-directories and files present in the current directory.

help : using this command we can know the working of any command.

clear : This command clears the terminal

Opening the OpenLane EDA tool using linux commands from the terminal:

![Screenshot from 2024-10-04 19-31-42](https://github.com/user-attachments/assets/8308cde6-0254-42cb-a143-9f4443f96a35)

Path:~/Desktop/work/tools/openlane_working_dir$ cd openlane
------

Design Preparation Step
----------------------
After entering into openlane we move to docker where we will access to all the tools available in openlane .After that we use the command to enter into interactive mode for step by step flow.

![image](https://github.com/user-attachments/assets/2848ed59-3ce0-4c43-bd8d-1eea6ab7451d)



![Screenshot from 2024-10-04 20-01-57](https://github.com/user-attachments/assets/0c6e47a3-5b1a-42d6-90f4-861b5c19a19a)

After that we import the the packages that are required for the design and setup for the design
In this we choosen the design as Picorv32a

![Screenshot from 2024-10-04 20-12-17](https://github.com/user-attachments/assets/31910c8c-3b56-4a6c-8d16-0275a8a57deb)

Reviewing files after design prep
---
In this lecture we reviewed the design picorv32a . Some parameters of the design like clockperiod , buffers, synthesis configuration , floor planning configuration using command below :

path:~/Desktop/work/tools/openlane_working_dir/openlane/designs/picorv32a/runs/04-10_14-38$ less config.tcl
--

![Screenshot from 2024-10-04 20-58-45](https://github.com/user-attachments/assets/25f5c16e-094a-45e1-974b-4c48d28f0e2a)

we explored other vrious options such tmp, results etc.,



