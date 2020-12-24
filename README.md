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


## SMD BOM

** WIP **