antares
=======

* DIN rail mount
* Atmel AT90CAN128
* 10Mbit/s Ethernet utilising MicroChip ENC28J60
* 42x I/O on 50-pin 2mm connector to daughter board (currently antares-I or antares-O) and 16-pin 2mm headers
* CAN-Bus
* RS485
* 6-pin 2mm ISP header
* 10-pin 1/20" JTAG header (optional)
* 6-pin 3.5mm connector for RS485, CAN-Bus and power supply
* 8-30V DC switching power supply
* Poor mans POE utilising spare pairs
* 2-layer PCB



antares-I
=========

* 32x input via optocoupler
* dry or powered inputs (jumper selectable) individually for sets of 4 inputs
* 50-pin 2mm connector to antares board
* 4x 10-pin 3.5mm connector for inputs
* 2-pin connector for power supply
* 32 LEDs showing input states
* 2-layer PCB



antares-O
=========

* 40x output via ULN2003 open collector driver
* 50-pin 2mm connector to antares board
* 50-pin 1/10" connector (or 2x 10-pin 3.5mm connector with only 16 outputs)
* 2-pin connector for power supply
* 40 LEDs showing output states
* 2-layer PCB



finderboard
===========

* 1-layer PCB
* adapter from antares-O to 4 finder DIN rail relais 
