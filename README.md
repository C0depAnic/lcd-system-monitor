# Cyber System Monitor

Display and monitor system information on an external, microcontroller-driven 16x2 LCD.

![lcd demo](/doc/img/demo.gif)

fork differencies
1. ready status for client (Arduino)
2. auto level backlit (Arduino) !in progress
3. show clock N date (Python)
4. status diode (Arduino) !in progress

## Requirements

### Dependencies

Arduino IDE for flashing the Arduino.

Python 3.4 or above, [psutil](https://pypi.org/project/psutil/), [pyserial](https://pypi.org/project/pyserial/).

Works on all Linux or BSD machines out of the box.


### Hardware

* 1x Arduino Nano + USB cable
* 1x [16x2 LCD] I2C controller version (other displays also) !in progress
* 1x photodiode
* 3x 220 Ohm resistor
* RGB diode !in testing

## Setup

Compile and upload `csm.ino` to your Arduino. !in progress
Set up the circuit like so:

![circuit diagram](/doc/img/circuit.svg) !in progress


## Roadmap
* monitor network interface load x2 !in progress

