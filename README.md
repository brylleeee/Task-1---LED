# Task-1---LED

## File: project1.ino

## Author: Creator

## Description:

This Arduino code is a basic example that demonstrates how to blink an LED connected to pin 13 of the Arduino board.

## Hardware Required:

-Arduino board
-LED
-220 ohm resistor

## Circuit:

-Connect the long leg (anode) of the LED to pin 13 through the 220 ohm resistor.
-Connect the short leg (cathode) of the LED to ground.

## Code Explanation:

### setup(): This function runs once when the Arduino board starts up.

pinMode(13, OUTPUT): Configures pin 13 as an output to control the LED.

### loop(): This function runs repeatedly in a loop.

digitalWrite(13, HIGH): Turns on the LED by setting pin 13 to high.
delay(2000): Pauses the program for 2 seconds.
digitalWrite(13, LOW): Turns off the LED by setting pin 13 to low.
delay(2000): Pauses the program for 2 seconds.

## Functionality:

The LED connected to pin 13 will blink on and off every 2 seconds.
