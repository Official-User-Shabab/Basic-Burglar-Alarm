# Basic-Burglar-Alarm
Simple alarm to catch out some wrongdoings with an arduino.

---

## Components

- Arduino Uno R3
- Male to Female jumper wires
- Red LED x1
- Buzzer x1
- PIR motion sensor
- USB cable

---

## Assembling hardware

- Put LED in Arduino board by putting positive leg into pin13 and ground in GND pin
- Using jumper wires, connect positive leg of buzzer into digital pin and short leg into GND pin
- Using jumper wires attach power pin of PIR sensor into 5V header on Arduino, ground pin to GND pin, and high/low output to a digital pin like pin2
- PIR sensor has 2 modes, determined by jumper. With the jumper over the pin marked H the sensor is in re-triggering mode - the output pin is HIGH whenever the sensor detects mode. With the jumper over the pin marked L the sensor is in blocking mode - the output pin is HIGH for 2.5s when it detects movement
- Set PIR sensor to L by moving the jumper if necessary

## Uploading code
