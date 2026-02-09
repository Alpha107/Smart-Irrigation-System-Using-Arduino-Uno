# Smart Irrigation System Using Arduino Uno

An automated irrigation system that monitors soil moisture and water levels to water plants efficiently. This project demonstrates sensor-based automation and actuator control.

---

## Introduction
The Smart Irrigation System is designed to optimize water usage in agricultural and gardening applications. A soil moisture sensor monitors the moisture level of the soil, and a water level sensor checks the availability of water in the reservoir. The Arduino Uno processes these readings and automatically controls a water pump to irrigate the plants when needed.

This project demonstrates automation, real-time decision making, and sensor integration. Smart irrigation systems help reduce water wastage, save labor, and ensure healthy plant growth.

---

## Components Used

| Component | Description | Purpose |
|-----------|------------|--------|
| Soil Moisture Sensor | Analog moisture detection sensor | Measures soil moisture level |
| Water Level Sensor | Conductive level sensor | Detects water availability |
| Arduino Uno | ATmega328P microcontroller | System controller |
| Water Pump | DC submersible pump | Supplies water to plants |
| Breadboard | Prototyping board | Circuit assembly |
| Jumper Wires | Connection cables | Electrical connections |
| Batteries | Power source | System power |
| Battery Holders | Battery mounting | Power management |

---

## System Diagrams

### Block Diagram
![Block Diagram](images/block_diagram.png)  
*The soil moisture sensor monitors the soil, and the water level sensor checks the tank. Arduino controls the water pump to irrigate plants when required.*

### Circuit Diagram
![Circuit Diagram](images/circuit_diagram.png)  
*Soil moisture and water level sensors are connected to Arduino analog/digital pins. The water pump is controlled via a relay or transistor circuit. Batteries provide power, and the breadboard is used for circuit assembly.*

---

## Problems Faced
- Corrosion of soil moisture sensor probes over time  
- Inaccurate readings due to different soil types  
- Power consumption issues with the water pump  
- Difficulty setting optimal moisture thresholds  
- Loose connections during breadboard prototyping  

---

## Future Improvements
- Replace resistive soil sensors with capacitive sensors for durability  
- Add LCD or OLED display for real-time monitoring  
- Integrate IoT using ESP32 for remote control and data logging  
- Use solar power for energy efficiency  
- Implement weather-based irrigation scheduling  
- Add mobile app notifications  

---

## Conclusion
The Smart Irrigation System using Arduino Uno successfully automates plant watering based on soil and water availability. The project improved understanding of sensor-based automation and actuator control. Despite minor challenges with sensor durability and power management, the system reliably irrigated plants, providing a foundation for advanced smart agriculture solutions.

---

## Images
*(Replace the placeholders with your actual images)*  
![Irrigation System Front](images/irrigation_front.png)  
![Irrigation System Top](images/irrigation_top.png)
