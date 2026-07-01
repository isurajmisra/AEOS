# ESP-IDF Skill

## Overview

ESP-IDF is the official Espressif IoT Development Framework for ESP32 and ESP8266 devices. This skill documents key concepts, tools, and patterns for embedded development with ESP-IDF.

## Core concepts

- Project structure: `main`, `components`, `build`, and `sdkconfig`.
- Build system: CMake-based workflow with `idf.py build`, `flash`, and `monitor`.
- FreeRTOS tasks and event loops.
- Peripheral drivers and configuration via `menuconfig`.
- OTA updates and secure boot.

## Best practices

- Keep firmware changes small and incremental.
- Use architecture diagrams for hardware and software interfaces.
- Document assumptions and configuration choices.
- Validate behavior with tests and hardware checklists.
