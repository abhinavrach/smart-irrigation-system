# smart-irrigation-system
This project is an automated irrigation system that uses a soil moisture sensor to control water supply. It ensures plants receive water only when needed, reducing wastage.

## Concept

This system uses sensor-based automation to manage irrigation:

- **Soil Moisture Sensor** – Detects moisture level in soil
- **Arduino Uno** – Processes sensor data
- **Relay + Pump** – Controls water flow automatically

### Why Smart Irrigation?

- Works only when soil is **dry**
- Prevents **overwatering**
- Saves **water and effort**
- Suitable for **gardening and agriculture**

---

## System Design

### Soil Moisture Sensor
- Outputs analog values based on moisture
- Helps determine dry or wet soil

### Arduino Uno
- Reads sensor data
- Compares with threshold value
- Controls relay output

### Relay Module
- Acts as a switching device
- Enables Arduino to control high-power pump

### Water Pump
- Supplies water to plants
- Activated only when required

---

## Components Used

- Soil Moisture Sensor
- Arduino Uno
- Relay Module
- Water Pump
- Power Supply
- Connecting Wires

---

## Working Principle

1. Soil moisture sensor measures moisture level
2. Arduino reads the sensor value
3. Value is compared with a predefined threshold
4. If soil is dry → relay activates → pump turns ON
5. If soil is wet → relay deactivates → pump turns OFF

---

## Applications

- Home gardening
- Agricultural irrigation
- Greenhouse systems
- Water conservation setups

---

## Future Improvements

- Add **IoT-based monitoring system**
- Integrate **mobile app control**
- Use **solar power supply**
- Deploy **multiple sensors for large areas**

---

## Author

Abhinav Racha Battuni  
RV College of Engineering (RVCE)

---

## Links

- Portfolio: https://abhinavrach.github.io/
- Project Repo: https://github.com/abhinavrach/smart-irrigation-system
