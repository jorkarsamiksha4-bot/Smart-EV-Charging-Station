# ⚡ Smart EV Charging Station

## 🧠 Overview
The **Smart EV Charging Station** is an Arduino-based prototype that demonstrates the concept of contactless and automated EV charging. It uses an **IR sensor**, **Tesla coil**, **LED indicators**, and an **I2C LCD display** to manage and visualize the charging process efficiently. The system automatically detects the vehicle presence and controls the power supply through the Arduino.

---

## ⚙️ Components Used
- **Arduino UNO**
- **16x2 I2C LCD Display**
- **IR Sensor**
- **LED (Indicator)**
- **Tesla Coil (Wireless Power Transfer)**
- **Resistors (for current limiting)**
- **Breadboard**
- **Jumper Wires**
- **5V Power Supply / USB Power**

---

## 🔩 Working Principle
1. The **IR Sensor** detects the presence of an EV (or any nearby object).  
2. When detected, the Arduino activates the **Tesla Coil**, transferring energy wirelessly to the receiver side.  
3. The **LCD display** shows "Charging ON" and the **LED** lights up to indicate active charging.  
4. Once the EV is removed or sensor signal is lost, the Arduino turns **OFF** the coil and displays "Charging OFF".  

---

## 💡 Features
- Automatic vehicle detection using IR sensor  
- Wireless energy transfer using Tesla Coil  
- Real-time charging status on LCD display  
- Visual indication using LED  
- Compact breadboard-based setup for demonstration  

---

## 🔋 Applications
- Wireless EV charging research and prototyping  
- Educational and academic demonstration projects  
- Arduino and IoT-based energy automation systems  

---

## 🚀 Future Scope
- Integration with IoT for remote monitoring and energy usage tracking  
- Solar energy input for eco-friendly charging  
- Improved wireless power efficiency using tuned coils  

---

## 🧰 Author
**Developed by: Samiksha Jorkar 
**Platform:** Arduino UNO  
**Category:** Embedded Systems / Energy & Automation Projects
