# ModuDeck

![image](https://github.com/user-attachments/assets/3f0b4d66-617f-496f-b1ba-f86319ed2fac)
![image](https://github.com/user-attachments/assets/37f4eb17-9645-4d3c-bcb7-d9b277be3080)
![image](https://github.com/user-attachments/assets/f0a909d5-0cff-4548-a8f7-148aaf38f352)

## A modular cyberdeck that supports multiple SBCS.
  - ### Modules
    - [Exoskeleton](##exoskeleton)
    -   [Compute Modules](##compute) 
        - [Pi 5](###pi-5)
        - [Pi zero 2 w](###pi-zero-2-w)
        - [Lattepanda Mu](###lattepanda-mu)
    - [Battery Modules](##battery)
      - [High Capacity](###2p4s)
      - [Low Capacity](###4s1p)
    - [Keyboard](##keyboard)
    - [Display](##display)
    - [How to assemble modules](##final-assembly)
  - [BOM](#bom) 
## What is the point
I set out to make a modular cyberdeck because I wanted to try to design something that doesnt follow the modern design trends of slimmer and less upgradeable and repairable computers. The modular concept helps alleviate these problems by making use of easily replaceable and upgradeable batteries and SBCs. This also solves the problem of many custom projects being very inconvenient to do maintenance on. For example, some people hotglue everything into place, making the project nearly impossible to work on. In this project, however, every part that you would need to replace is easily replaceable with m3 and m2.5 hardware, securing it in place. 

# Assembly Instructions
- ## Exoskeleton
  - ### Printing
1. Print Both main case peices vertically
2. Print both rear cases flat or vertically if you have elephants foot issues
3. Assemble both sides of each part together using either superglue, plastic welding, or your preferred method of attaching 3d prints.
4. Use m3 hardware to secure the back on once done with wiring exept leave these 3 holes unscrewed, they are for mounting the modules.
5. ![image](https://github.com/user-attachments/assets/548c0564-2f25-40dd-abd0-01465cd6cda7)
6. ![image](https://github.com/user-attachments/assets/ff62195c-1aec-4a41-bd82-4093bc74212a)


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
10. Screw the pi into the mounting posts with m2.5 hardware.
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
11. Screw the pi into the mounting posts with m2.5 hardware.
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
11.  Screw on the top using m3 hardware.
  - ### 4s1p
    - Same as 2p4s, but instead of having cell pairs, just use individual cells. 
- ## Keyboard
- ![image](https://github.com/user-attachments/assets/c7141ee0-f2cb-4047-bc69-fcb0b232d4ae)

1. Solder all of the switches onto the PCB.
2. Solder all of the diodes onto the PCB.
4. Solder the Pi Pico onto the bottom of the PCB.
5. Use [QMK Configurator](https://docs.qmk.fm/configurator_step_by_step) to configure and flash the board [here](https://config.qmk.fm/#/rart/rart75hs/LAYOUT_ansi_split_bs)
6.  Desolder the pi picos usb port.
7. Solder a 28awg wire onto each of the usb pads.
8. Solder the other ends of the wires coming from the USB to the magnetic connector in this order, from left to right, on the pin side vcc, Data-, Data+, Ground.
9. Press the magnetic connector into its slot where the compute module clips in.
10. ![image](https://github.com/user-attachments/assets/405afd9f-6964-4e02-aafa-8ef415c3af7e)
11. Slide the keyboard in and screw it down using m3 hardware.
- ## Display
1. Print both screen mount halves and secure them together using ca plastic welding or your preferred adhesive.
2. Use double-sided tape to secure the driver board to the back of the screen on the left side, away from the compute module.
3. Position the screen in the main case and put the scren mount around it aligned with the screw holes.
4. Screw in m3 hardware from the top of the case in all of the holes.
5. Plug the HDMI coming from the compute module bay into the display board.
6. Use 18awg wire to the 12V XT60 from the battery module bay to the power pads on the driver board after desoldering the barrel plug.
- ## Final Assembly
1. Slot the compute module into the left of the cyberdeck making sure all of the connectors line up.
2. Use 2 m3 bolts to secure the module in place.
3. ![image](https://github.com/user-attachments/assets/0535d8d2-0bf3-43aa-a2d4-4d7c89185349)
4. Slot the battery in, turned off, into the slot on the right, making sure all of the connectors line up.
5. Screw in one m3 bolt to secure it in place
6. ![image](https://github.com/user-attachments/assets/bee713ff-f16f-4670-ac2b-776bf844eb31)

# BOM

| Item |	Quantity |	Total price+Shipping | Use In project	| Item Source
| ------------- | ------------- | ------------- | ------------- |------------- |
| General |||||			
| Display |	x1 |	$64.19 |	displays | https://www.ebay.com/itm/145841358470? |
| m3 hardware kit |	x1	| $7.99|	Mount most things	| https://www.amazon.com/Hincell-540pcs-Button-Washers-Stainless/dp/B0D1CV8V9Y?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&smid=A8FI3NPCLLLAU&gQT=2&th=1|
|m2.5 4mm |	x1 |	$1.86 |	mount the pis if you use them |	https://www.aliexpress.us/item/3256805692588351.html?spm=a2g0o.productlist.main.9.70f8PGXgPGXgES&algo_pvid=f41aab01-f6bc-4ebf-8b6a-e709e2d91d9e&algo_exp_id=f41aab01-f6bc-4ebf-8b6a-e709e2d91d9e-8&pdp_ext_f=%7B%22order%22%3A%22141%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21USD%212.63%212.63%21%21%212.63%212.63%21%402101c67a17493315079284241e4c88%2112000034678326960%21sea%21US%214381910819%21X&curPageLogUid=wPZG0AeXcYEt&utparam-url=scene%3Asearch%7Cquery_from%3A|
|18awg wire	| x1 |	$13.76 | most wiring |	https://www.amazon.com/Nilight-Electrical-Conductor-Extension-Amplifier/dp/B0CYZPW42Q?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&smid=ATVPDKIKX0DER&gQT=1&th=1 |
|28awg wire	| x1 |	$7.99 |	Usb wiring |	https://www.amazon.com/Fermerry-Stranded-Silicone-Cables-Electrical/dp/B089CR4SDM?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&smid=AMHYOXF0C8EDF&gQT=1&th=1 |
|12awg wire |	x1 |	$3.94 |	Battery wires |	https://www.aliexpress.us/item/3256807129117447.html?spm=a2g0o.productlist.main.3.7ab0a156NrdRf6&algo_pvid=3e03f551-26de-40a9-8a5d-b5bc81856425&algo_exp_id=3e03f551-26de-40a9-8a5d-b5bc81856425-2&pdp_ext_f=%7B%22order%22%3A%223673%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21USD%216.91%213.94%21%21%2149.31%2128.11%21%402101c5b117493323478534303ed134%2112000040296899199%21sea%21US%214381910819%21X&curPageLogUid=HZUS3mRJr7EU&utparam-url=scene%3Asearch%7Cquery_from%3A|
|Filament	| x1 |	$20 |	be every printed part |	Idk wherever you get filament |
|Nickel strip| x1| $5.69 | build batteries| https://www.amazon.com/MECCANIXITY-Nickel-Battery-Soldering-Welding/dp/B0CVXLLGCQ?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&smid=A1NR50YASSZD11&gQT=1&th=1|
|Total|| $125.42 |||
||||||
|Keyboard Parts	| | | | |	
|Pi pico |	x1 |	$4 |	drive the keyboard | https://www.adafruit.com/product/4864 |
|Keyboard pcb	| x5 |	$35.47 |	Be a keyboard PCB |	PCBWAY |
|Gateron Red	| x100	| $34.40 |	Be switches |	https://www.aliexpress.us/item/3256805905674117 |
|Keycaps |	x80 |	$14.16 |	Be keycaps |	https://www.aliexpress.us/item/3256807292808339.html? |
|Shipping |	$6.99	| | | |
|Total | |$95 | | |		
||||||
|Battery Module 2p4s |||||				
|DC-DC converter |	x2 |	$10.60 |	Convert the battery voltage to 12v/5v |	https://www.dfrobot.com/product-2599.html |
|18650s | x8 |	$29.28 |	be batteries |	https://www.18650batterystore.com/products/samsung-25r-18650?variant=37119890063511 |
|Bms |	x1 |	$1.75 |	be a bms for the batteries |	https://www.aliexpress.us/item/ |
|RA11131121 |	x1 |	$0.69 |	power switch |	https://www.mouser.com/ProductDetail/E-Switch/RA11131121?qs=QtyuwXswaQhes8SRTBHYHQ%3D%3D&mgh=1&gQT=1 |
|373 |	x1 |	$0.95 |	charger |	https://www.mouser.com/ProductDetail/Adafruit/373?qs=GURawfaeGuDDC%2FyE6Usrdw%3D%3D |
|Total| |	$43.27	| | |	
|Battery Module 4s1p |||||	
|DC-DC converter |	x2 |	$10.60 |	Convert the battery voltage to 12v/5v |	https://www.dfrobot.com/product-2599.html |
|18650s | 	x4 |	$18.59 |	be batteries |	https://www.18650batterystore.com/products/samsung-25r-18650?variant=37119890063511 |
|Bms |	x1 |	$1.75 |	be a bms for the batteries |	https://www.aliexpress.us/item/ |
|RA11131121 |	x1 |	$1.06 |	power switch |	https://www.aliexpress.us/item/3256808591861621.html?spm=a2g0o.productlist.main.4.bbaa3f0amP9fEs&aem_p4p_detail=202506110835012802225516499430001432280&algo_pvid=22d13a10-315a-4e88-a7fb-5fc6e3a68f98&algo_exp_id=22d13a10-315a-4e88-a7fb-5fc6e3a68f98-3&pdp_ext_f=%7B%22order%22%3A%22115%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21USD%212.08%211.06%21%21%2114.86%217.57%21%402101c67a17496561013444578ee284%2112000046629830173%21sea%21US%214381910819%21X&curPageLogUid=AIpxTC6KBWSG&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=202506110835012802225516499430001432280_1 |
|Total | | $32.00 |	| |	
||||||
|Pi zero 2 w compute | | | | |
|pi zero 2 w	| x1 |	$23.00 |	Main computer |	https://www.adafruit.com/product/5291 |
|mini hdmi to hdmi adapter |	x1 |	$6.99 |	adapt the HDMI |	https://www.amazon.com/Micro-Adapter-Female-Support-Raspberry/dp/B09HS74STL?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A1NY347U90KP9S&gQT=1 |
| USB hub and pi cooloer	| x1 |	$9.99 |	Cool the pi and breakout usb |	https://www.amazon.com/Raspberry-iUniker-Aluminum-Passive-Adapter/dp/B09XK36QNB/140-2177712-4060064?pd_rd_w=vyCyv&content-id=amzn1.sym.4c8c52db-06f8-4e42-8e56-912796f2ea6c&pf_rd_p=4c8c52db-06f8-4e42-8e56-912796f2ea6c&pf_rd_r=MV80K33AW3WARSHK5YW9&pd_rd_wg=EWgEt&pd_rd_r=25190511-4df9-42d1-908e-41de3ecdd1ec&pd_rd_i=B09XK36QNB&psc=1 |
|Total |	| $39.98 |	| | |	
||||||	
|Pi 5 Compute | | | | |
|Pi 5 8gb |	x1 |	$96.98 |	main computer |	https://www.pishop.us/product/raspberry-pi-5-8gb/?searchid=0&search_query=pi+5|
|Micro HDMI to Standard HDMI |	x1 |	$4.25 |	hdmi adapter |	https://www.pishop.us/product/micro-hdmi-to-standard-hdmi-adapter-white/|
|Cooler	| x1 |	$8.95 |	cool the pi |	https://www.pishop.us/product/dedicated-all-in-one-aluminum-cooler-for-raspberry-pi-5-pwm/?searchid=0&search_query=pi5+cooler|
|Total | | $110.18 | | |	
||||||
|Lattepanda Mu Compute| | | | |	
|Lattepanda Mu with lite carrier and active cooler |	x1 |	$220.00 |	main computer |	https://www.dfrobot.com/kit-004.html|
|Total| |	$220.00| | |		
