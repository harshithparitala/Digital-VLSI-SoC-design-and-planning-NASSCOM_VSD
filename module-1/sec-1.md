Title: How to talk to Computers 

In the lecture 1 we disscused about Introduction to QFN-48,Package,Die,Core and IP's

![image](https://github.com/user-attachments/assets/58f6da45-1282-499a-89b8-46f8cf8eab01)

The highlighted one is the PROCESSOR/SOC connected along with other peripherals or interfacess .
The entire board can be describes as shown in figure 

![image](https://github.com/user-attachments/assets/ab6dfa84-ecd6-4ca8-8565-3fc9368b617b)

This consists of ADC, DAC, SRAM, UART,VCC/GND,I2C,SDRAM Chip and etc., there are there in typical ardunio board 

If , we open up on chip,it will loook like
![image](https://github.com/user-attachments/assets/e536e46e-0213-4c7d-9109-4d525ec55292)


Lets take an example of package ,QFN-48 .The QFN-48 Package has 48 pins and size of the package as 7mm 
![image](https://github.com/user-attachments/assets/4a11f75d-72b2-486f-b5d5-2a74e2a16b6b)

If we openup the chip we have various kinds of components such as Pads, Die,Core etc.,

Pads: A component through which we can send the signals inside or outside of the chip\

Die: defines the entire size of the chip

Core: the centre of the chip  where all the digital logics are placed

If we take an example of RISC-V,it look like

typical chip consists of Pll,AD,DAC,SRAM  and these are called foundaryIPS

FoundaryIPS :Foundry IP refers to intellectual property (IP) blocks and libraries used in foundries, which are companies that manufacture integrated circuits

SOC,SPI Are called MACROS which are purely digital blocks.



