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

$ sudo chmod 777 ttyUSB* 
(if you know which port you have connected just mention the port instead of *)

Then open the **dynamixel wizard 2.0** and go to Options and tick all the boxes and make set ID range to scan to 20.

Then go and scan, if its new motor it will detect it in 57600 bps its slef you can skip and if not wait untill we get the motor.

