---
title: esphome-VOC sensor
date-published: 2026-01-28 14:22:59 +0100
type: sensor
standard: global
board: esp32
difficulty: 1
made-for-esphome: false
project-url: https://github.com/starelectronic/esphome-VOC.git
---

<p align="center">
  <img src="/pic/VOC_sensor_front.jpg">
  </p>

# ESP32-WROOM-32E VOC sensor

The VOC sensor is designed to provide real-time data on air quality, utilizing the Sensirion´s SGP40 VOC sensor. This device is ideal for environmental monitoring with high accuracy and low power consumption.

### Features:
- Utilizes ESP32-WROOM-32E with 8MB meory.
- Measures VOC level (up to 500%).
- Includes WS2812B LED on GPIO02.
- Includes a Buzzer on GPIO13.
- Serial communication via UART.

### Quick Start Guide:

### Used Pins in Default Configuration

| GPIO | Function | Description |
|------|----------|-------------|
| GPIO02 | RGB LED | WS2812 addressable LED |
| GPIO13 | Buzzer | Built-in buzzer |
| GPIO21 | SDA | I2C SDA pin |
| GPIO22 | SCL | I2C SCL pin |

  - [ESPHome Configuration File](esphome-VOC.yaml)

### Purchase:
For purchasing information, please visit our [Product Page](https://www.soselectronic.com/sk-sk/products/sos-electronic/esp32-devkiti2c-voc-476094).
