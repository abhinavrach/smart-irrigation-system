# smart-irrigation-system
This project is an automated irrigation system that uses a soil moisture sensor to control water supply. It ensures plants receive water only when needed, reducing wastage.

Smart Irrigation System using Arduino

A simple automated irrigation system that uses a soil moisture sensor and an Arduino Uno to control water supply, ensuring efficient water usage and reduced manual effort.

Concept

This system automates plant watering based on soil moisture conditions.

Soil Moisture Detection – Measures water content in soil
Automated Control – Turns pump ON/OFF based on moisture level
Why Automation?
Reduces water wastage
Eliminates manual monitoring
Ensures optimal plant growth
System Design
Soil Moisture Sensor
Detects moisture level in soil
Outputs analog signal
Determines whether soil is wet or dry
Arduino Uno
Processes sensor data
Compares with predefined threshold
Controls relay accordingly
Relay Module
Acts as an electrical switch
Controls high-power water pump using low-power signal
Water Pump
Supplies water to plants
Activated only when required
Components Used
Arduino Uno
Soil Moisture Sensor
Relay Module
Water Pump
Power Supply
Connecting Wires
Working Principle
Soil moisture sensor reads moisture level continuously
Arduino receives analog data from the sensor
Value is compared with a preset threshold
If soil is dry → relay is activated → pump turns ON
If soil is wet → relay is deactivated → pump turns OFF
Applications
Agricultural irrigation
Home gardening systems
Greenhouse automation
Water conservation systems
Future Improvements
Integration with WiFi for remote monitoring
Mobile app-based control
Weather-based irrigation logic
Solar-powered system
Multiple sensor deployment
Author

Abhinav Racha Battuni
RV College of Engineering (RVCE)

Links
Portfolio: https://abhinavrach.github.io/
Project Repo: https://github.com/abhinavrach/smart-irrigation-system
