# 9V QRP BADGE Transciever

Based on the schematic and work of Jeff Anderson, [K6JCA](https://www.qrz.com/db/k6jca)
and [this blog post](http://k6jca.blogspot.com/2009/08/9v-qrp-transceiver.html).

Variant of the smaller [9V battery-sized version](https://github.com/zortness/9v_cw_tx).

## About

This is a very simple, direct conversion CW transciever that will operate on the 40m 
amateur radio band. It requires an external speaker or headphones, an external antenna,
and a power source between 5 and 12 volts.

**This is still a work in progress.**

Changes from the micro version:
* larger credit card or badge size (55mm X 85mm)
* includes 7-element low pass filter (LPF) based on the QCX design with T-37-2 toroids
* includes ATTiny402 to control keying output, and reading buttons
* includes buttons for DIT and DAH 
* includes 9x2 header pinout for exposing and adding functionality (or fancy covering)


## Schematics

![Power schematic](https://raw.githubusercontent.com/zortness/9v_cw_badge/master/power.png)

![Receiver schematic](https://raw.githubusercontent.com/zortness/9v_cw_badge/master/receiver.png)

![Audio schematic](https://raw.githubusercontent.com/zortness/9v_cw_badge/master/audio.png)

![Amplifier schematic](https://raw.githubusercontent.com/zortness/9v_cw_badge/master/amplifier.png)

![Keyer schematic](https://raw.githubusercontent.com/zortness/9v_cw_badge/master/keyer.png)


## Board Layouts

![Board layout](https://raw.githubusercontent.com/zortness/9v_cw_badge/master/board.png)


## ProtoBoard Prototype 

This prototype is extremely sensitive to capacitance (even touch), and lacks a true ground plane,
though I added through-hole-pins to act as grounding feet on my steel work table. 

![proto board](https://raw.githubusercontent.com/zortness/9v_cw_tx/master/proto_board.jpg)


## SMD Prototypes

I've gone through a few SMD prototypes and made a number of pad and routing mistakes. I also chose
a number of parts poorly or just completely misread the units on the part values (nH != uH, pF != uF). 

I will update when one of the boards can operate without any further modification.

![proto board](https://raw.githubusercontent.com/zortness/9v_cw_tx/master/smd_proto_01.jpg)
![proto board](https://raw.githubusercontent.com/zortness/9v_cw_tx/master/smd_proto_02.jpg)
![proto board](https://raw.githubusercontent.com/zortness/9v_cw_tx/master/smd_proto_03.jpg)
![proto board](https://raw.githubusercontent.com/zortness/9v_cw_tx/master/smd_proto_04.jpg)

## SMD BOM

** WIP **