# PiConnector
 Connects Power, Data and ADXL to a Pi for 3D Printing
 
 PiConnector

![image](https://github.com/DrRonnyy/PiConnector/blob/main/PiConnectorPic1.png)
![image](https://github.com/DrRonnyy/PiConnector/blob/main/PiConnectorPic2.png)

Warning: Use this board at your own risk! It has not been widely tested but it works for me!

The PiConnector board makes it easy to connect power and data from your MCU and an ADXL345 board to your Raspberry Pi. It makes it easy to connect because you don’t have to count the GPIO pins when connecting, making errors less likely to happen. It can be used solely for power, solely for ADXL or for both. It makes it convenient for using one ADXL board on several printers.
This has been tested to power a Raspberry Pi 3, please be cautious on connecting a Pi that consumes more power, it should work on a Raspberry Pi 4 but some people report that powering a Pi 4 by “GPIO” isn’t reliable.

BOM: 
2	JST-HX 4-Pin female
1	JST HX 2-Pin female
1 	Female Header 2x20 pin (2.54mm) (Pololu 1037)

