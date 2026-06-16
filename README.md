# STM32 GNSS/IMU Telemetry Logger

## Overview

This project is a custom STM32 based sensor board for collecting motion and position data, logging it locally, whilst transmitting selected telemetry wirelessly. The motivation for this project originally stemmed from the idea of being able to log and wirelessly transmit the orientation and position data of a drone. 

The board will feature an onboard IMU, GNSS module, microSD storage, and an external LoRa module to transmit to a receiving device. The  motivation for this project is to build a complete embedded hardware system to build upon the microcontroller breakout board I previously worked on, and touching base on a few areas of electronics I'm interested in. 

## Planned Features

- STM32 microcontroller
- Onboard 6-axis IMU
- Onboard GNSS module
- microSD card slot for local logging
- USC-C input for power
- 3V3 voltage regulation
- SWD programming/debug header
- Status LEDs
- Reset button
- Connector for external LoRa module
- Computer-side visualization for orientation and GNSS data

## Project Status

Planning stage

> Read about more detailed project specifications under docs/project-spec.md
