# Settuping-dynamixel_work-bench-for-diff_drive-robot

**GOAL:**
Moving the both the dynamixel servos in the same direction.

**Required:**
Dynamixel Motors - 2, 
USB Cable - 1, 
U2D2 - 1, 
Power Hub -1 , 
12v 5A SMPS Power Supply - 1, 
Connecting wires - required.

**Setup dynamixel for operation:**

**Step 1:** Connect one dynamixel motors with power supply u2d2 power hub using the dynamixel mannual.

**Step 2:** Install dynamixel wizard to your ubuntu 20.04 machine. (https://emanual.robotis.com/docs/en/software/dynamixel/dynamixel_wizard2/)

**Step 3:** Connect the USB to with PC and open the open termial and follow the following steps. 

$ cd /dev
![Screenshot from 2022-10-16 20-38-30](https://user-images.githubusercontent.com/115935026/196043134-a7ec5ffd-64b0-4c42-bba6-912fbcacb391.png)


$ sudo chmod 777 ttyUSB* 
(if you know which port you have connected just mention the port instead of *)
![Screenshot from 2022-10-16 20-40-47](https://user-images.githubusercontent.com/115935026/196043214-2737da24-5b5c-4c0c-ba97-5d68800c135e.png)


Then open the **dynamixel wizard 2.0** and go to Options and tick all the boxes and make set ID range to scan to 20.
![Screenshot from 2022-10-16 20-41-51](https://user-images.githubusercontent.com/115935026/196043280-7d88e866-bb45-4e75-a674-9b7078894a18.png)


Then go and scan, if its new motor it will detect it in 57600 bps its slef you can skip and if not wait untill we get the motor.

