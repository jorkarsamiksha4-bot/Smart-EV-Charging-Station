# 🔌 Smart EV Charging Station

## 🧠 Overview
The **Smart EV Charging Station** is an Arduino-based system designed to automatically manage the charging process of electric vehicles using IR sensors, relays, and an LCD display. It provides a simple and efficient way to control charging operations and ensures safe energy management.

---

## ⚙️ Components Used
- **Arduino Uno**
- **IR Sensor**
- **16x2 I2C LCD Display**
- **2-Channel Relay Module**
- **LED Indicators**
- **12V/5V Power Supply**
- **Load (EV Simulation using a Bulb or Motor)**

---

## 🔩 Working Principle
1. When an EV (vehicle) is detected by the **IR Sensor**, the Arduino activates the **relay**, turning **ON** the charging circuit.  
2. The **LCD** displays "Charging ON", and a green **LED** lights up.  
3. When the vehicle is removed, the IR sensor stops detecting the object.  
4. The **relay turns OFF**, power to the charging circuit is cut, and a red **LED** blinks to indicate "Charging OFF".

---

## 💡 Features
- Automatic EV detection using IR sensor  
- Relay-based charging control  
- Real-time status on LCD display  
- Energy-efficient and safe operation  
- Easy to integrate with IoT for future expansion  

---

## 🔋 Applications
- Home-based smart EV charging setups  
- Prototype models for IoT and automation projects  
- Academic projects in Electronics and Telecommunication  

---

## 🚀 Future Scope
- Integration with IoT platforms for remote monitoring  
- Adding wireless power transfer module  
- Solar energy integration for green charging solutions  

---

## 🧰 Author
**Developed by: Samiksha Jorkar 
**Platform:** Arduino Uno  
**Category:** Embedded Systems / Renewable Energy Projects
