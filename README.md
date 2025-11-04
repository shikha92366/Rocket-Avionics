<!-- HEADER -->
<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=800&height=100&duration=4000&lines=Rocket+Avionics+System+🚀" />
</h1>

<h3 align="center">🛰️ <b>Team Sudarshan</b> || <b>IN-SPACe Rocket Competition</b></h3>

<p align="center">
  <img src="https://github.com/user-attachments/assets/243cc12c-3af6-42d1-a547-a28f60496a19" width="400" alt="Rocket Avionics System PCB"/>
</p>


<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Platform-Raspberry%20Pi%20Pico%202-orange?style=for-the-badge"></a>
  <a href="#"><img src="https://img.shields.io/badge/Designed%20with-EasyEDA-blue?style=for-the-badge"></a>
  <a href="#"><img src="https://img.shields.io/badge/Communication-XBee%203%20Pro%20%7C%20SIM800L-lightgreen?style=for-the-badge"></a>
  <a href="#"><img src="https://img.shields.io/badge/Category-Rocketry%20Avionics-red?style=for-the-badge"></a>
</p>

---

We designed the **Rocket Avionics System** as a compact and reliable onboard electronics suite for our rocket, **Trishul**.  
It manages real-time telemetry, navigation, and event control — acting as the core intelligence that powers every stage of flight.


---

## ⚙️ Core Features

- **🧠 Dual-Controller Architecture:**  
  Combines Raspberry Pi Pico 2 (flight control) and Arduino Nano 33 BLE Sense (sensor fusion).  

- **📡 Communication Links:**  
  XBee 3 Pro for short-range telemetry and Quectel EC200U CN for 4G-based backup communication.  

- **🛰️ NavIC GPS Integration:**  
  Ensures precise location tracking using India’s indigenous satellite system.  

- **📊 Multi-Sensor Suite:**  
  Includes IMU (BNO085), BMP390 barometer, INA219 power sensor, MAX31856 thermocouple, and DS3231 RTC.  

- **💾 Data Logging:**  
  SD Card support for mission-critical data storage and redundancy.  

- **🔋 Power Management:**  
  Dual voltage regulation (5V / 3.3V) with over-current protection and MOSFET-based event triggering.  

---

## 🧩 Components Used

| Component | Function |
|------------|-----------|
| Raspberry Pi Pico 2 | Primary flight computer |
| Arduino Nano 33 BLE Sense | Secondary Flight Controller |
| XBee 3 Pro | RF telemetry communication |
| Quectel EC200U CN 4G | Sends location after landing |
| BNO085 IMU | Orientation sensing |
| BMP390 | Altitude and barometric pressure |
| INA219 | Power monitoring |
| MAX31856 | Temperature measurement |
| DS3231 | Real-time clock |
| SD Card Module | Data logging |
| Li-Po Battery | Power source |
| MOSFET/Relay Board | Pyro & event control |

---

## 🛠️ System Overview  

<p align="center">
  <img src="https://github.com/user-attachments/assets/02c55ac8-49f7-4923-b85f-099acecf7516" width="1000" alt="System Diagram">
</p>

**Flight Functions:**
1. Sensor data acquisition  
2. Real-time telemetry transmission  
3. Event triggering (parachute, separation, etc.)  
4. Power and thermal management  
5. Mission data recording  

---
## 🛠️ Working

Video - 

schematic

pcb layout



---
## ⚡ Power and Event Control  

- **Input:** 7.4V Li-Po battery  
- **Output:** 5V and 3.3V regulated lines  
- **Control:** MOSFET/Relay-based event channels  
- **Indicators:** LEDs and buzzer feedback for system status  

---

## 💡 Key Highlights

- Modular and lightweight PCB design  
- Dual-MCU architecture for fault tolerance  
- NavIC GPS and dual telemetry support  
- Real-time logging and power monitoring  
- Designed & simulated entirely in **EasyEDA**

---

## 👨‍🚀 Developed By

**Team Sudarshan**  
- Shikha

<p align="center">
  <a href="https://inspace.gov.in/" target="_blank">
    <img src="https://img.shields.io/badge/Supported%20by-IN--SPACe-blue?style=for-the-badge">
  </a>
</p>

---

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=30&center=true&vCenter=true&width=700&height=70&duration=4000&lines=Innovation+in+Every+Flight+🚀;Bye✨" />
</h1>
