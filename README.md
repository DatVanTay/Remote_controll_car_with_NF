
# Remote_controll_car_with_NF
Controll car by joystick with communicate NF {Radio}

## Hardware
## + Car
- Arduino Uno
- Arduino Motor Shield L293D
- Display oled 128x32
- Module NRF24L01
- Module shows battery level
- Motor DC 12V
- Robot Tank Crawler Chassis DIY
- Plastic Battery Holder Storage Box Case with Leads
- Pin 18650
## + Controller
- Arduino Nano
- Joystick
- Display oled 128x64
- Module NRF24L01
- Switch
- Plastic Battery Holder Storage Box Case with Leads
- Pin 18650
## Software
## Visual studio code

-Platformio extension


## Library

Install library with platformio

```bash
 //Board Arduino 
#include <Arduino.h>

//Library for motor
#include <AFMotor.h>
#include <Servo.h>

//Library for radio
#include <RF24.h>
#include <nRF24L01.h>
#include <SPI.h>

//library for display
#include <Adafruit_SSD1306.h>
#include <Wire.h>
#include <Adafruit_GFX.h>

```
## Authors

- [@hapqy](https://github.com/DatVanTay)

## Feedback

If you have any feedback, please reach out to us at duyduy3852528@gmail.com
