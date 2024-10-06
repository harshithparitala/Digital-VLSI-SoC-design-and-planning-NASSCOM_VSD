Power Planning
-----
Let us consider the circuit as Black box (macron). If this macron is repeated multiple times on the chip and there will be current demand for each and every macron

Let's there is a signal driven to load signal is transition from logic 0 to logic 1. we have to make sure that the signal path maintains same signal that load receives.

let connect the power supply, these bllocks are tapped to vdd and ground respectively 

Since there is no De coupling capacitor near path the power supply need to take care of sinal. Powe supply is far to the path and there will be voltage drop happens 

let's assume it is a 16-bit bus , If the bit is logic 1 it says the capacitor which is being charge to vdd similary logic 0 refers to capacitor discharged to ground

Let's  say it is connected to inverter , the  output will be all the capacitors are charged  to logic 1 and will discharge to logic 0 and it will cause a bump called as ground bounce 


similarly logic 0 to logic 1  cause voltage droop

It is due to power is coming from single source, if there are multiple power supplies we can ensure that it will give current or drop current to the circuit 

