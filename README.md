# Steelseries apex 7 TLK repair
For about two years ago i bought a keyboard for each of my children.
I chose steelseries because i don't like unnecessary consumption and i thought this keyboard would last for decades. 
Clearly i had wrong. 
<br>
After two years of normal use, my daughter's keyboard died in the middle of a game.
<br><img src="https://github.com/peter-strom/apex7/blob/7f77f5aedef96dc7562f0562d800369d29a9c53c/doc/overview.jpg" width="600" >
<img src="https://github.com/peter-strom/apex7/blob/7f77f5aedef96dc7562f0562d800369d29a9c53c/doc/b1.jpg" width="600" >
<br>
Disasemmbled the keyboard and found some testpads that was easy to meassure on. <br>
* The 5V pad gave me only 0.8V. <br>
* The fuse F1 looked okay.<br>
* B1 (inductor) had an open circuit (probable for a filter to pass EMC)..<br>
Replaced the inductor with a 0 ohm resistor, and plugged the keyboard in to a usb charger. <br>
* The 5V pad now gave me 5V.
<br><br>

<img src="https://github.com/peter-strom/apex7/blob/abfc9cf51497f0392749b4e602e1d57260660c41/doc/mcu2.png" width="600" >
<br>One of the MCUs woke up and the other one was dead. V-MCU2 only gave me 0.7V. Turned out that the keyboard needed communication from a computer to enable the second MCU.  
<br><br>

<img src="https://github.com/peter-strom/apex7/blob/7f77f5aedef96dc7562f0562d800369d29a9c53c/doc/buc.jpg" width="600" >
<br>
Didn't take long before it smelled burned circuits. The hot parts were located near the oled display. Removed the inuctor (L1), buck converter(U5) and the diod(D128) that looked damaged from the heat. Everything works except the oled. 
<br><br>

<img src="https://github.com/peter-strom/apex7/blob/7f77f5aedef96dc7562f0562d800369d29a9c53c/doc/flir.jpg" width="600" >
<br> Normal temps on the other parts.
<br><br>

<img src="https://github.com/peter-strom/apex7/blob/7f77f5aedef96dc7562f0562d800369d29a9c53c/doc/working.jpg" width="600" >
<br>
Atleast the keyboard is working again.  I have asked steelseries if they can hand over the part numbers for the damaged parts. Finger crossed. 

<br><br>to be continued...
