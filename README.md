# Arduino Drone Project

This repository documents my early embedded systems practice as I work toward building a drone from scratch.

The goal of this project is to build experience with:

- Arduino programming
- Sensor reading
- Breadboard circuits
- Embedded systems
- Hardware debugging
- Engineering documentation

## Current Progress

### Photoresistor Sensor Reading Test

I completed my first Arduino sensor reading test using a photoresistor, breadboard, resistor, jumper wires, and an Elegoo UNO R3 board.

The goal was to read real-world light changes using the Arduino analog input pin A0.

## Components Used

- Elegoo UNO R3 board
- Breadboard
- Photoresistor
- Resistor
- Jumper wires
- Arduino IDE

## Circuit Setup

The photoresistor and resistor were connected as a voltage divider:

```text
5V ---- photoresistor ---- A0 ---- resistor ---- GND

