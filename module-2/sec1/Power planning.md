Power Planning
-----
Let us consider the circuit as Black box (macron). If this macron is repeated multiple times on the chip and there will be current demand for each and every macron

![Screenshot 2024-10-06 124925 - Copy](https://github.com/user-attachments/assets/cdffd4e9-fe6e-49c2-be8f-8a964c51ec24)

Let's there is a signal driven to load signal is transition from logic 0 to logic 1. we have to make sure that the signal path maintains same signal that load receives.

![Screenshot 2024-10-06 124934 - Copy](https://github.com/user-attachments/assets/3878b9b6-3720-45b1-9c70-4857848efab6)

let connect the power supply, these bllocks are tapped to vdd and ground respectively 

Since there is no De coupling capacitor near path the power supply need to take care of sinal. Powe supply is far to the path and there will be voltage drop happens 
![Screenshot 2024-10-06 124954 - Copy](https://github.com/user-attachments/assets/d8df73ad-051f-45aa-87a1-9e591140017a)

let's assume it is a 16-bit bus , If the bit is logic 1 it says the capacitor which is being charge to vdd similary logic 0 refers to capacitor discharged to ground
![Screenshot 2024-10-06 125020](https://github.com/user-attachments/assets/78c47552-ddb0-4c7d-9ca0-cb6ccfdc71da)

Let's  say it is connected to inverter , the  output will be all the capacitors are charged  to logic 1 and will discharge to logic 0 and it will cause a bump called as ground bounce 

![Screenshot 2024-10-06 125036](https://github.com/user-attachments/assets/9e573661-fd58-4beb-a06c-51b49e9ab351)

similarly logic 0 to logic 1  cause voltage droop

![Screenshot 2024-10-06 125051](https://github.com/user-attachments/assets/8f8d48c2-6d7c-4b1c-9fc6-20431602b571)

It is due to power is coming from single source, if there are multiple power supplies we can ensure that it will give current or drop current to the circuit 

![Screenshot 2024-10-06 125102](https://github.com/user-attachments/assets/615a5621-4f42-40c2-b01f-90fa24bf5c21)

![Screenshot 2024-10-06 125120](https://github.com/user-attachments/assets/fcea00dd-8e24-449f-b497-b5131f0f25bc)
