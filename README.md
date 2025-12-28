# ESP32DevCard v1 — Credit-Card Sized Powerhouse

A deployment-oriented ESP32-S3 development board for engineers building systems, not desk toys. Real power delivery, integrated sensing, and full breakout in a compact 70 × 50 mm footprint.

The goal: eliminate the wiring mess that causes 80% of prototype failures.

---

## Why This Exists

Most ESP32 boards assume your prototype ends at a breadboard. The moment you attach motors, LED arrays, or anything drawing real current, they fall apart.

This solves that problem directly:

* 4-layer stackup for signal and power integrity
* Multiple power injection points
* Clean grounding discipline and ESD protection
* On-board peripheral support for validation without external modules

This is the board you use when reliability matters from the first test.

---

## Core Capabilities

* ESP32-S3-MINI-1-N8 (Wi-Fi + BLE, dual core)
* ENS210 temperature/humidity sensor (I²C)
* WS2812B RGB indicator (GPIO48)
* USB-C for power/programming with protection circuitry
* 44 usable GPIOs on dual headers
* High-current 5V and 3.3V rails
* 4-layer PCB for controlled return paths

---

## Technical Specifications

| Parameter         | Value            |
| ----------------- | ---------------- |
| Dimensions        | 70 × 50 mm       |
| Layers            | 4                |
| MCU Flash         | 8 MB             |
| Operating Voltage | 3.3 V            |
| Status LED        | WS2812B (GPIO48) |
| On-board Sensor   | ENS210           |

---

## Getting Started

1. Plug in via USB-C
2. Flash using the ESP-IDF toolchain or PlatformIO
3. Access peripherals immediately (I²C sensor, indicator LED)

