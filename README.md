# ESP32 UART Event Example (ESP-IDF)

This project demonstrates how to use the ESP-IDF UART driver with an event queue to handle UART events in an interrupt‑driven system.

The firmware reads data from UART0 and echoes it back to the monitoring console.

## Features

- UART event queue handling
- Interrupt-driven UART communication
- FreeRTOS queue integration
- Compatible with ESP32 family chips

## Hardware

- ESP32 development board
- USB cable
- ESP-IDF installed

## Build
```bash
idf.py build
