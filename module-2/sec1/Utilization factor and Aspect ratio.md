Titile :Utilization factor and Aspect ratio
--------------------------------------------

In the physical design flow the first step is defining the height and width of the core
![Screenshot 2024-10-06 103517](https://github.com/user-attachments/assets/55cbf2f4-132a-4c1c-9cc3-e1c8d83e9402)

Let's take an example of basic netlist consists of two flipflops and logic gates

![Screenshot 2024-10-06 103537](https://github.com/user-attachments/assets/e0e31ced-9a20-47e2-ae46-70af543fad70)

In this we are dependent on the dimensiions of logic gates and flipflops ,
lets assume standard cells are having an area of 1sq.unit and same are for flipflops as well

![Screenshot 2024-10-06 103552](https://github.com/user-attachments/assets/dd9a07af-9991-450d-a626-b13241f0caf1)

If we bring all the standard cells and flip flops together and caluclate the are area gives the minium area occupied by the netlist

![Screenshot 2024-10-06 103615](https://github.com/user-attachments/assets/bcda6bb0-055f-495d-8914-8afcb65d0a77)

If we place the netlist inside the core , we have seen that netlist completely occupies the core which means it has 100% utilization  of the core 

![Screenshot 2024-10-06 103640](https://github.com/user-attachments/assets/d520aa3a-f585-4649-a52b-2c6a5691a615)

Utilization factor is given by Area occupied by the netlist to Total Area of core

![Screenshot 2024-10-06 103640](https://github.com/user-attachments/assets/9f9cd759-85fb-4967-837a-a47003fa7b53)

Aspect Ratio is given by Height to the Width of the core .

Another example where the dimensions of the netlist is same and core is different 
![Screenshot 2024-10-06 103713](https://github.com/user-attachments/assets/38922f37-b0dd-40ce-bee5-beffd35e40aa)

In this case the utilization factor is 0.5
And Aspect ratio is also 0.5

![Screenshot 2024-10-06 103746](https://github.com/user-attachments/assets/5168dd59-b0d1-4952-a1bf-0d5750bf4cd5)
