Pin placement and logical cell blockage 
-------------
Lets take an example with two different flipflops with different colors and another section with different flipflop and clocks .

drive by clock 1

driven by clk 2

along with there are pre placed cells connect with din and output are connect to logic gates and another pre plced cell block b takes input from clks and give clock out


Asuume another section with same design which has two flipflops and two different clks  and another one with same but opposite clocks and block c pre placed cell is connected 

Complete design look like 

We connect clk 1 and clk2 , 

We fill the area between core and die with these ports 

We place all the input ports on left hand side and output at right hand side  and ordering will be random

Pin placement creates hand checking frontend and backend ,

Clk ports are bigger in size  because it is continously driving all thw cells and sends the signals to all the flipflops 

The area between die and core blocks for cell placement and it is reserved for pins .


