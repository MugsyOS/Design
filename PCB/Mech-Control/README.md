
The Mech Control PCB’s primary function is controlling the stepper motors in the cone mechanism and spout assembly. A while back I realized that having a few smaller and more function specific boards was a way better option then the single monolithic “Brain Board”. Keeps the designs much simpler and allows revisions to single controllers without having to also update everything else.

**Components:**

-   Nano Microcontroller
    
-   2x DRV8825 Stepper Drivers
    
-   2x SS34 SCHOTTKY Protection Diodes
    
-   2x10 pin headers for IO bridge
    
-   12v input
    
-   RJ45 Jack for connecting cone mech
    
-   TRRS Jack for connecting spout
    

**IO Bridge:** The IO bridge exposes all of the unused Nano’s pins except for reset and VIN:

-   2x 3V3
    
-   2x 5V
    
-   4x GND
    
-   A0
    
-   A1
    
-   A2
    
-   A4 / SDA
    
-   A5 / SCL
    
-   A6
    
-   A7
    
-   D0
    
-   D1
    
-   D12
    
-   D13
    
-   AREF
    

All of the analog pins can also be used as digital pins as needed.

**Board Files:** The schematic and board files have been uploaded to the design repo here.

I’m going to organize the schematic a little better for readability’s sake. And the routing around the io bridge is a little more rat-nesty than I like, so will end up revising that section. But as long as this version tests out ok, I’ll probably hold off until the rest of the work is completed.

Please note that these are in Fusion/Eagle format. I’ll eventually move over to KiKad for everything, but Im just way less experienced with it, so it will be quite a while until I can dedicate some time to ramping up.
