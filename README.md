#  Dynamic Parking Availability System

![Progress](https://img.shields.io/badge/Status-Completed-brightgreen)

**🟢 Hardware Project – Fully Implemented & Tested**

A real-time smart parking monitoring system using **PIC16F877A**, **ultrasonic & IR sensors**, **DHT11**, and **LCD interface**. Designed for efficient parking management and easy scalability.

---

##  Objectives

- Detect real-time parking slot occupancy.
- Count vehicle entry and exit using IR sensors.
- Display available slots and environmental conditions.
- Provide visual feedback via LEDs for quick status checking.
- Build a modular, low-cost embedded system prototype.

---

## System Workflow

### 1. Sensor Interfacing
- **Ultrasonic sensor** → Measures distance to detect if slot is occupied.
- **IR sensors** → Track vehicle entry and exit.
- **DHT11 sensor** → Measures temperature and humidity.

### 2. Processing (PIC16F877A)
- Debouncing for IR sensors.
- Timer-based distance measurement.
- Checksum validation for DHT11.
- Slot availability counter.

### 3. Output Systems
- **LCD display** for:
  - Free slots  
  - Temperature  
  - Humidity  
- **LED indicators**:
  -  Red → Slot occupied  
  -  Green → Slot free  

---

## 🔌 Hardware Components

- PIC16F877A Microcontroller  
- HC-SR04 Ultrasonic Sensor  
- IR Entry/Exit Sensors  
- DHT11 Temperature & Humidity Sensor  
- 16×2 LCD Display  
- Red & Green LEDs  
- 5V DC Power Supply  

---

##  Results

### ✔ Performance Summary
- Accurate entry/exit counting  
- Ultrasonic sensor accuracy: **±0.5 cm**  
- DHT11 data validated via checksum  
- LCD update time: **< 200 ms**  
- No miscounts during rapid vehicle sequences  

---

##  Future Enhancements
- Add Wi-Fi or Bluetooth for IoT-based monitoring
- Build a mobile app to show available parking slots in real-time
- Expand system to support multiple parking slots
- Replace ultrasonic sensor with ToF (Time-of-Flight) sensors for higher accuracy
- Add cloud connectivity for data logging and usage analytics
- Integrate automated barrier control for entry/exit

---

##  Contributors

Shivani K C

Vishnu K Mahesh

Namitha Madhu
  
