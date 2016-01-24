# Breadboard Arduino
### ATmega 328p with internal 8mhz clock###

This version of the Breadboard Arduino boards file is compatible with Arduino 1.6.7. It is designed to work with an ATmega328p using the internal 8mhz oscillator. Always burn the bootload on a new chip, regardless of whether or not you plan to use it. This is required to set the fuse settings to the internal clock. The bootloader works identically to the Arduino Uno bootloader.

There are 3 ways to install these boards files into Arduino.


#### Boards Manager ####
Add this link to your boards manager. 

```
https://github.com/oshlab/Breadboard-Arduino/raw/master/avr/boardsmanager/atmega328p_internal_8mhz.json
```
Download through the boards manager. 

#### Git version###
Navigate to your Arduino hardware file directory. For windows this is located in Documents/Arduino/hardware/. Clone this repository into the hardware directory using .

```
git clone https://github.com/oshlab/breadboard.git
```

#### Download ####
Just download this repository and add it to your hardware file directory. For windows this is located in Documents/Arduino/hardware/



OSH Lab, LLC


