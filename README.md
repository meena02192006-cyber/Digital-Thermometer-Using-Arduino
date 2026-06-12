# Digital Thermometer Using Arduino

## Project Overview

This project is a Digital Thermometer developed using Arduino Uno, DHT22 Temperature Sensor, LCD1602 I2C Display, and a Buzzer. The system continuously monitors the surrounding temperature and displays the measured value on an LCD screen. When the temperature exceeds a predefined threshold, an alert message is displayed and the buzzer is activated.This project was designed and tested using the Wokwi Arduino Simulator.

## Features

* Real-time temperature monitoring
* Temperature display on LCD screen
* High-temperature alert system
* Buzzer notification for threshold crossing
* Easy to simulate using Wokwi

## Components Used

* Arduino Uno
* DHT22 Temperature Sensor
* LCD1602 I2C Display
* Buzzer
* Jumper Wires

## Circuit Connections

### DHT22

* VCC → 5V
* DATA → D2
* GND → GND

### LCD1602 I2C

* VCC → 5V
* GND → GND
* SDA → A4
* SCL → A5

### Buzzer

* Positive (+) → D8
* Negative (-) → GND

## Working Principle

1. The DHT22 sensor measures the ambient temperature.
2. Arduino reads the temperature data from the sensor.
3. The measured temperature is displayed on the LCD screen.
4. If the temperature exceeds 35°C, the buzzer is activated.
5. The LCD displays a "HIGH TEMP ALERT" warning message.

## Output

### Normal Condition

* Temperature below 35°C
* LCD displays temperature and "Normal Temp"

### Alert Condition

* Temperature above 35°C
* LCD displays "HIGH TEMP ALERT"
* Buzzer turns ON

## Applications

* Room temperature monitoring
* Industrial temperature monitoring
* Smart home systems
* Educational and embedded systems projects

## Technologies Used

* Arduino IDE
* Embedded C / Arduino Programming
* Wokwi Simulator

## Simulation

Add your Wokwi project link here:

Wokwi Project: [https://wokwi.com/projects/466595719866763265]

## Conclusion

The Digital Thermometer project successfully measures and displays temperature using the DHT22 sensor. The system also provides an alert mechanism through a buzzer when the temperature exceeds the predefined threshold. This project helps in understanding sensor interfacing, LCD communication, and embedded system programming using Arduino.

## Author

Meena
