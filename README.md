# ESP32 Onboard LED Blink

A simple beginner project using ESP32 and Arduino IDE to blink the onboard LED.

## Overview

This project demonstrates basic GPIO output control on an ESP32 development board.

The program controls the LED connected to GPIO 2 and switches it ON and OFF with a 5-second delay between state changes.

## Hardware Requirements

- ESP32 development board with an onboard LED connected to GPIO 2
- USB cable
- Computer with Arduino IDE

## Software Requirements

- Arduino IDE
- ESP32 board support in Arduino IDE

## How to Run

1. Open `esp32-onboard-led-blink.ino` in Arduino IDE.
2. Select your ESP32 board.
3. Select the correct USB port.
4. Upload the program.
5. Observe the onboard LED.

## How It Works

- GPIO 2 is configured as an output.
- The program waits for 5 seconds.
- The LED is switched ON.
- After another 5 seconds, the LED is switched OFF.
- The cycle repeats continuously.

**Note:** The onboard LED pin may vary depending on the ESP32 board model.

## Author

Mehrab

## Future Improvements

- Use `millis()` instead of `delay()`.
- Make the blink interval configurable.
- Add a project demonstration video.

