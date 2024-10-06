Pin placement and logical cell blockage 
-------------
Lets take an example with two different flipflops with different colors and another section with different flipflop and clocks .

drive by clock 1
![image](https://github.com/user-attachments/assets/04f25190-aee1-420d-ae24-532bb20005f8)
driven by clk 2

![image](https://github.com/user-attachments/assets/cbbb8b61-dd31-4924-94a8-42d4544da4cf)

along with there are pre placed cells connect with din and output are connect to logic gates and another pre plced cell block b takes input from clks and give clock out

![image](https://github.com/user-attachments/assets/6ae6eb14-0cf7-42e8-b9a4-5e5b2f1802a8)


Asuume another section with same design which has two flipflops and two different clks  and another one with same but opposite clocks and block c pre placed cell is connected 

![image](https://github.com/user-attachments/assets/fd4aaf1f-674c-4b42-9068-4b5d117e98d1)

![image](https://github.com/user-attachments/assets/80cc86fb-fce2-47c6-a3ec-8f590370d2a1)


Complete design look like and  We connect clk 1 and clk2 

![image](https://github.com/user-attachments/assets/25830606-bb08-4a2f-9571-c669b1757432)

We fill the area between core and die with these ports and 
We place all the input ports on left hand side and output at right hand side  and ordering will be random

![image](https://github.com/user-attachments/assets/02c405b4-99b4-4ad4-91d6-0a28bfebdde1)

Pin placement creates hand checking frontend and backend ,
Clk ports are bigger in size  because it is continously driving all thw cells and sends the signals to all the flipflops 
The area between die and core blocks for cell placement and it is reserved for pins .


