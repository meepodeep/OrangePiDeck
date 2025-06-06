# Assembly Instructions
- ## Exoskeleton
  - ### Printing
1. Print Both main case peices vertically
2. Print both rear cases flat or vertically if you have elephants foot issues
3. Assemble both sides of each part together using either superglue, plastic welding, or your preferred method of attaching 3d prints. 
  - ### Wiring
1. Press fit all of the connectors including, HDMI, XT60, and the magnetic 4pin adafruit connector.
   
   ![image](https://github.com/user-attachments/assets/0fd08194-80e9-40ad-867a-078b374c4c35)
   ![image](https://github.com/user-attachments/assets/30f84252-43d8-494d-9bb3-9530e62c0f8d)
   ![image](https://github.com/user-attachments/assets/ba18828a-95c4-429c-9c11-e86e0e8a968e)
  
3. Solder the 12v supply for the xt60 on the battery to the 12v supply on the compute xt60 with 18awg wire.
4. Solder the 5v supply for the xt60 on the battery to the 5v supply on the compute xt60 with 18awg wire.
   
   ![image](https://github.com/user-attachments/assets/de2e18f7-fb5b-44db-a2de-fa9dcce30943)
   ![image](https://github.com/user-attachments/assets/10fbd645-9f47-4903-bd5d-a3345cbce0c1)
   
- ## Compute
  - ### Pi 5
 
  ![image](https://github.com/user-attachments/assets/80697535-dd90-45e4-90ad-57e10585d5e2)
  
1. Print the pi 5 compute model.
2. Assemble the cooler.
3. Solder 28awg wire to the 4 USB pins from the Bottom of the USB 2.0 connector on the set of pins closest to the edge of the board.
4. Remove the casing from the micro HDMI to HDMI adapter.
5. Press the HDMI into the casing.
6. Solder the 5v and gnd connections from the gpio to the + and - terminals onto an xt60 connector using 18awg wire. Press the connector into the 5v part of the module.

  ![Raspberry-Pi-5-Pinout--1](https://github.com/user-attachments/assets/1bf2fb04-5506-45d7-aa4a-e6c779ec7be8)
  
7. Press the 5v Xt60 into the case.
8. Solder the other ends of the wires coming from the USB to the magnetic connector in this order, from left to right, on the pin side. Ground, Data+, Data-, Vcc.
9. Press the Magnetic connector into the case.
10. Screw the pi into the mounting posts with m2 hardware.
  - ### Pi zero 2 w

![image](https://github.com/user-attachments/assets/083dfda2-22cb-4347-8fe5-6b9f540754b6)

1. Print the Pi Zero Compute model.
2. Assemble the cooler
3. Decase the USB hub.
4. Solder 28awg wire to the pins of the USB port at the end of the hub.
5. Solder the other ends of the wires coming from the USB to the magnetic connector in this order, from left to right, on the pin side. Ground, Data+, Data-, Vcc.
6. Press the Magnetic connector into the case.
7. Solder the 5V and GND connections from the GPIO to the + and - terminals onto an xt60 connector using 18awg wire.
8. Press the connector into the 5V part of the module.

![j8header-zero](https://github.com/user-attachments/assets/cbbb74f6-314b-48d0-9814-83c6bb143a6f)

9. Decase the mini HDMI adapter on the big HDMI side.
10. Press the HDMI into the case, and plug in the mini HDMI.
11. Screw the pi into the mounting posts with m2 hardware.
  - ### Lattepanda mu
1. Print the Lattepanda compute module.
2. Assemble the Panda, cooler, and devboard.
3. Desolder the Barrel jack connector
5. Solder 28awg wire to the 4 USB pins on the bottom of the furthest USB connector from the edge of the board on the port that is covered by the case.

![image](https://github.com/user-attachments/assets/83d93c86-eff8-4e53-b216-7cfeed9b19e8)

6. Solder 18awg wire to the + and - of the barrel jack and solder them to the + and - of an xt60.
7. Press that into the 12V supply port on the module.
8. Solder the other ends of the wires coming from the USB to the magnetic connector in this order, from left to right, on the pin side. Ground, Data+, Data-, Vcc.
9. Desolder the hdmi port and solder 28awg magnet wire or normal wire onto each pin (i know its annoying) and also to the corresponding pins on the board, make these wires long enough to reach the other side of the case.
10. Press the HDMI port into the case.

- ## Battery
  - ### Build
1. Print battery module cover.
2. Print battery module.
  - ### 2p4s
    - Wiring
- # BEFORE DOING THIS MAKE SURE ALL OF THE CELLS ARE AT THE SAME VOLTAGE SO YOU DONT EXPLODE YOU HOUSE!!
1.  Wire 4 pairs of cells in a 1p configuration by spot welding nickel strips in between the cells.
2.  ![image](https://github.com/user-attachments/assets/f82f0284-b86a-4918-99c3-48dce45d935b)
3.  Wire all 4 of those 1p cells in series into a 2p4s Configuration by spot welding nickel strips, this is the green section of the diagram.
4.  Solder 5 equal-length wires of 22awg to the BMS and to the parts of the battery; these are the purple wires in the diagram.
5. ![image](https://github.com/user-attachments/assets/409fbfce-569a-4919-8638-6654f78267a2)
6.  Solder a 12awg wire to the - terminal on the BMS.
7.  Solder a 12awg wire to the + terminal on the BMS and to the power switch, solder another 12awg wire to the other side of said switch, and press it into the case.
8.  ![image](https://github.com/user-attachments/assets/1eb0b9ab-41d2-4184-9acc-a713c4eb69a5)
9.  Follow the wiring diagram from step 8 in order to complete the battery, then make sure to insulate all of the connections with your preferred method.
10.  Press both XT60s into their respective ports. 
  - ### 4s1p
    - Same as 2p4s, but instead of having cell pairs, just use individual cells. 
- ## Keyboard
