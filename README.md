# Boba Fett ESB Chest Display

DIY replica of the Boba Fett *The Empire Strikes Back (ESB)* chest display, based on an ATmega328 microcontroller.

## Hardware

- ATmega328 microcontroller
- Two 10-segment LED displays (Opto Supply OSX10201-R)
- Five 7-segment LED displays (Opto Plus OPD-S3011)
- Multiplexed LED control using five control signals
- Custom PCB or prototyping board

## Firmware

The ATmega328 firmware controls the LED sequence. The display pattern is based on research by RafalFett:

[ESB Chest Display Sequence — The Dented Helmet](https://www.thedentedhelmet.com/forums/threads/esb-chest-display-sequence.20061/)

The code is an independent implementation of the researched sequence.

## Build Notes

The circuit has been tested on a prototyping board and a custom PCB.

Check the display pinout and segment configuration before assembly, as compatible-looking displays may have different electrical characteristics.

## Disclaimer

This project is provided for hobbyist and educational purposes. Hardware and software are provided "AS IS", without warranty. Use at your own risk.

Commercial use is not permitted. This project, including its hardware designs and firmware, must not be used for commercial purposes, sold, or incorporated into products intended for sale without the author's prior written permission.
