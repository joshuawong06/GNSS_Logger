# GNSS Flight Telemetry Logger

## Overview

This project is a small embedded telemetry and data-logging system for collecting GNSS position data, logging sensor data, and transmitting low-rate telemetry over LoRa.

The goal is to build practical experience with embedded systems, avionics-style telemetry, PCB design, sensor interfaces, and post-test data analysis.

## Planned Features

- Read GNSS position/time data over UART
- Log data to a microSD card
- Transmit selected telemetry over LoRa
- Read IMU data for local logging and filtering experiments
- Monitor basic system health such as packet count, sensor status, and supply voltage
- Design a custom PCB with USB-C power, 3.3 V regulation, SWD programming, GNSS, LoRa, IMU, and SD card

## System Architecture

```text
GNSS ─┐
IMU  ─┼──> MCU ───> microSD logging
      │        └──> LoRa telemetry
      │        └──> SWD debug/programming
      └──> optional system-health monitoring
