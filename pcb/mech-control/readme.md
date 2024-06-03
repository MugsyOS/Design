![image](https://github.com/MugsyOS/Design/assets/179913/b7bff805-70db-4a3c-9fd2-44232a351f67)

**Components:**
* Nano Microcontroller
* 2x DRV8825 Stepper Drivers
* 2x10 pin headers for IO bridge
* 12v input
* 12v pass through
* 2x 47uf electrolytic capacitors
* 3x 100nf decoupling capacitors
* RJ45 Jack for connecting cone mech
* TRRS Jack for connecting spout

⠀**IO Bridge:** The IO bridge exposes all of the unused Nano’s pins except for reset and VIN:
* 2x 3V3
* 2x 5V
* 4x GND
* A0
* A1
* A2
* A4 / SDA
* A5 / SCL
* A6
* A7
* D0
* D1
* D12
* D13
* AREF

All of the analog pins can also be used as digital pins as needed.
**Board Files:** The schematic and board files have been uploaded to the design repo here.
