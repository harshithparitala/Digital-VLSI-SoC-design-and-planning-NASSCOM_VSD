Decoupling Capictors:
------
After placing the pre placed cells in the core , we need to surround them with the Decoupling capacitors .

![Screenshot 2024-10-06 120830](https://github.com/user-attachments/assets/ea3485d6-07ca-4da4-a1b7-000c4a5024ed)

 Lets consider this circuit is a part of any block of pre placed cells , whenever any gate switches from logic 0 to logic 1 there is some amount of current that demands , there is some capacitance setting over gate that capacitence needs to completely charge to represent logic 1 , this amount of charge is sent by power supply 
 Suppouse if the transition happening from logic 1 to logic 0, it is the responsibility of vss to take amount of charge .The capacitor will discharge 

![Screenshot 2024-10-06 120848](https://github.com/user-attachments/assets/7c7aabdb-32e8-40f5-86b8-25db971dba76)

 There will be some voltage drop across the wire and if the voltage vdd' is should be noise margin .
 Any voltage lies between Vil and Vih is undefined region , it's also called grey region.it can go either logic 0 or logic 1
 
![Screenshot 2024-10-06 120939](https://github.com/user-attachments/assets/2b4668c0-5f7f-4147-9e27-14ab81329360)

 We can ensure that voltage never lies in undefined region with the help of Decoupling capacitors , These capacitors decouples the circuit from main supply
 
![Screenshot 2024-10-06 120952](https://github.com/user-attachments/assets/918978d7-d1b1-4949-959f-76c8d7fb7a69)

 whenever switching happen decoupling capacitor will the current to circuit and these are placed very close to the circuit 

 ![Screenshot 2024-10-06 121012](https://github.com/user-attachments/assets/c8149a7c-8595-47ac-9f08-39a67413a1d7)

