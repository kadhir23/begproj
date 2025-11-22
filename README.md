📌 Overview

This project is an Underwater Monitoring System built using a Raspberry Pi, designed to measure and display real-time:

TDS (Total Dissolved Solids)

pH Level

Water Temperature

The values are continuously analyzed and displayed on a 16×2 I2C LCD, making it ideal for aquariums, underwater quality checks, environmental monitoring, and IoT-based water analysis.

This repository contains the full code and instructions needed to set up and deploy the system.

🧰 Features

✔️ Real-time monitoring of water quality
✔️ High-accuracy readings using ADS1115 ADC
✔️ Waterproof DS18B20 temperature sensing
✔️ pH and TDS calibration compatible
✔️ LCD display for portable visualization
✔️ Python-based (Raspberry Pi)
✔️ Simple, modular, clean code

🛠️ Hardware Used

Raspberry Pi (any model with GPIO support)

ADS1115 Analog-to-Digital Converter

TDS Sensor

pH Sensor

DS18B20 Waterproof Temperature Sensor

16×2 I2C LCD

Jumper wires, breadboard, 4.7kΩ resistor (for DS18B20)


📡 How It Works

The Raspberry Pi reads analog signals from the TDS and pH sensors through the ADS1115 ADC.
Temperature is read digitally from the DS18B20 sensor.
The system performs compensation, calibration formulas, and then displays:
