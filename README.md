# STM32 Temperature Monitoring System

## Overview
This project implements a real-time temperature monitoring system using STM32 (STM32F103C8T6) and LM35 sensor.

## Features
- Analog temperature sensing using ADC
- Real-time temperature calculation
- LED indication when temperature exceeds threshold (30°C)

## Hardware Used
- STM32F103C8T6 (Blue Pill)
- LM35 Temperature Sensor
- LED + Resistor

## Working Principle
The LM35 sensor outputs an analog voltage proportional to temperature (10mV/°C).  
The STM32 ADC converts this analog signal into a digital value (0–4095).  
The system calculates temperature and turns ON an LED if it exceeds 30°C.

## Code Highlights
- HAL ADC configuration
- Voltage calculation using ADC resolution
- Threshold-based GPIO control

## Future Improvements
- UART output to display temperature on PC
- LCD display integration
- IoT-based monitoring
  
## Author
Sneha V


## A
