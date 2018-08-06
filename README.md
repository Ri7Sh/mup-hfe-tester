# mup-hfe-tester
Problem Statement:
Design a microprocessor transistor hFE tester. The system has to display the hFE value of NPN transistors. The transistor under test (TUT) is to be inserted in the socket, and its base is energized with a current from a device DI.
 The current I produced by the device DI, can be controlled by supplying it with a DC voltage V. The relationship is as follows:
 [ I = V*10-4  A]
The emitter of the transistor is grounded, and the collector is connected to a 2.2K resistor, whose other end is connected to the +5V supply. The Voltage drop across a 2.2K resistor is measured and this is related to the hFE by the following relation:
[ HFE *I *2200 = Voltage Drop ] 
The hFE value should be displayed on a LCD display. If the hFE value is less than 50, an alarm should be sounded 2 seconds.
