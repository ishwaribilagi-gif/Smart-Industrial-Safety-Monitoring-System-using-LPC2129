# Smart Industrial Safety Monitoring System using LPC2129

## Project Overview
The Smart Industrial Safety Monitoring System is an embedded systems project developed using the LPC2129 ARM7 microcontroller. It continuously monitors industrial conditions using multiple sensors and detects potential hazards to improve workplace safety.

## Features
- Real-time temperature monitoring using the LM35 sensor.
- Human movement detection using a PIR sensor.
- Fire detection using a flame sensor.
- Threshold-based hazard detection.
- LCD display for sensor readings and system status.
- LED indicators and buzzer alerts for unsafe conditions.
- Continuous monitoring of the industrial environment.

## Technologies & Tools
- **Microcontroller:** LPC2129 (ARM7)
- **Programming Language:** Embedded C
- **IDE:** Keil µVision
- **Communication:** UART
- **Peripherals:** GPIO, ADC, LCD
- **Hardware:** LM35, PIR Sensor, Flame Sensor, LCD, LEDs, Buzzer

## Working Principle
1. The LM35 sensor measures the surrounding temperature.
2. The PIR sensor detects human movement.
3. The flame sensor detects fire conditions.
4. The LPC2129 reads and processes the sensor data.
5. The system checks the readings against predefined safety conditions.
6. If a hazardous condition is detected, the buzzer and LED indicators provide alerts.
7. Sensor readings and system status are displayed on the LCD and UART terminal.

## Hardware Components
- LPC2129 ARM7 Development Board
- LM35 Temperature Sensor
- PIR Motion Sensor
- Flame Sensor
- 16x2 LCD Display
- LEDs
- Buzzer
- Connecting Wires

## Applications
- Industrial workplace safety.
- Factory and manufacturing unit monitoring.
- Fire and hazard detection.
- Industrial automation systems.

## Project Structure
```text
Smart-Industrial-Safety-Monitoring-System/
├── main.c
├── delay.c
├── gpio.c
├── lcd.c
├── uart.c
├── adc.c
├── sensors.c
├── header.h
└── README.md
```

## Project Objective
To develop a microcontroller-based safety monitoring system that detects hazardous industrial conditions and provides immediate alerts through visual and audio indicators.

## Author
**Ishwari Sampatakumar Bilagi**
