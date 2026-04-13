# Smart Room Temperature Control System

## Objective

To simulate an automatic room temperature control system using STM32, where fan operation is controlled based on temperature conditions.

## Hardware Used

* STM32 Nucleo Board
* DHT11 Temperature and Humidity Sensor
* Fan
* LED
* Buzzer
* OLED Display

## Components and Purpose

* **DHT11 Sensor** → monitors room temperature and humidity
* **Fan** → automatic cooling when temperature increases
* **LED** → warning indication during high temperature
* **Buzzer** → alert during threshold crossing
* **OLED Display** → continuously displays temperature and humidity values

## Working Principle

* DHT11 sensor reads room temperature and humidity.
* OLED display alternates temperature and humidity values continuously.
* When temperature crosses the defined threshold, fan turns ON automatically.
* LED glows to indicate high temperature condition.
* Buzzer generates alert sound during abnormal temperature rise.

## Example Display Output

TEMP: 28C
HUM: 65%

## Real-Life Application

This simulates automatic room cooling systems used in homes, laboratories, server rooms, and storage environments.

## Development Platform

* STM32CubeIDE
* STM32 HAL Library
