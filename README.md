# Breadboard Arduino
### ATmega 328p with internal 8mhz clock###

**Important: when using this, you must select the "Burn Bootloader" function from the tools menu in Arduino the first time and burn the bootloader with an AVR programmer. This is needed even if you are not going to use the Arduino bootloader because it sets the fuse settings for the internal clock. **

This version of the Breadboard Arduino boards file is compatible with Arduino 1.6.7. It is designed to work with an ATmega328p using the internal 8mhz oscillator. The bootloader works identically to the Arduino Uno bootloader.

There are 3 ways to install these boards files into Arduino.


#### Boards Manager ####

Add this link to your boards manager. 

```
https://raw.githubusercontent.com/oshlab/Breadboard-Arduino/master/avr/boardsmanager/package_oshlab_breadboard_index.json
```
Download through the boards manager. This is the easiest method.

#### Git version###
Navigate to your Arduino hardware file directory. For windows this is located in Documents/Arduino/hardware/. Clone this repository into the hardware directory using .

```
git clone https://github.com/oshlab/breadboard.git
```

#### Download ####
Just download this repository and add it to your hardware file directory. For windows this is located in Documents/Arduino/hardware/



OSH Lab, LLC
http://oshlab.com


