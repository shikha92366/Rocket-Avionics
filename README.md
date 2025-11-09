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
  <a href="#"><img src="https://img.shields.io/badge/Communication-XBee%20S3B%20Pro%20%7C%204G%20EC200U-lightgreen?style=for-the-badge"></a>
  <a href="#"><img src="https://img.shields.io/badge/Category-Rocketry%20Avionics-red?style=for-the-badge"></a>
</p>

---

We designed the **Rocket Avionics System** as a compact and reliable onboard electronics suite for our rocket, **Trishul**.  
It manages real-time telemetry, navigation, and event control — acting as the core intelligence that powers every stage of flight.

---

## ⚙️ Core Features

- **🧠 Dual-Controller Architecture:**  
  Raspberry Pi Pico 2 (primary flight computer) + Arduino Nano 33 BLE Rev Sense 2 (secondary controller).

- **📡 Communication Links:**  
  XBee **S3B Pro** for RF telemetry and Quectel EC200U CN for 4G-based backup communication.

- **🛰️ NavIC GPS Integration:**  
  Accurate tracking using India’s satellite navigation system.

- **📊 Multi-Sensor Suite:**  
  BNO085 IMU, BMP390 barometer, INA219 power sensor, MAX31856 thermocouple, DS3231 RTC.

- **💾 Data Logging:**  
  SD Card module for mission-critical storage.

- **🔋 Power Management:**  
  5V/3.3V regulation with MOSFET-based pyro & event control.

---

## 🧩 Components Used

| Component | Function |
|------------|-----------|
| Raspberry Pi Pico 2 | Primary Flight Computer |
| Arduino Nano 33 BLE Rev Sense 2 | Secondary Controller |
| XBee S3B Pro | RF Telemetry |
| Quectel EC200U CN | 4G-based backup location |
| BNO085 | Orientation IMU |
| BMP390 | Altitude & pressure |
| INA219 | Power monitoring |
| MAX31856 | Temperature |
| DS3231 | RTC |
| SD Card Module | Data logging |
| Li-Po Battery | Power source |
| MOSFET Board | Event/Pyro control |

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

### ✅ **Video Demonstration**
<p align="center">
  <a href="https://github.com/shikha92366/Rocket-Avionics/blob/main/Easy%20Eda%20Schematic%20Layout/rocket%20avionics%20working%20video.mp4" target="_blank">
    <button style="background-color:#4CAF50;color:white;padding:10px 20px;border:none;border-radius:4px;font-size:16px;">
      Watch Working Video
    </button>
  </a>
</p>

---

### ✅ **Schematic Layout**
<p align="center">
  <a href="https://github.com/shikha92366/Rocket-Avionics/tree/main/Easy%20Eda%20Schematic%20Layout" target="_blank">
    <button style="background-color:#4CAF50;color:white;padding:10px 20px;border:none;border-radius:4px;font-size:16px;">
      View Schematic Layout (EasyEDA)
    </button>
  </a>
</p>

---

### ✅ **PCB Layout**
<p align="center">
  <img src="https://raw.githubusercontent.com/shikha92366/Rocket-Avionics/refs/heads/main/Easy%20Eda%20Schematic%20Layout/pcb_layout.jpg" width="600" alt="PCB Layout">
</p>

---

## ⚡ Power and Event Control  

- **Input:** 7.4V Li-Po Battery  
- **Outputs:** 5V and 3.3V regulated  
- **Event Control:** MOSFET-based pyro channels  
- **Indicators:** LEDs and buzzer  

---

## 💡 Key Highlights

- Modular & lightweight PCB  
- Dual-MCU architecture for safety  
- Dual telemetry (RF + 4G)  
- NavIC GPS support  
- Designed entirely in **EasyEDA**  

---

## 👨‍🚀 Developed By

**Team Sudarshan**

- Shikha  
- Riya Verma  
- Lavitra Sahu  
- Rahul Kumar  
- Arya Mishra  
- Mohd Faiz  

<p align="center">
  <a href="https://inspace.gov.in/" target="_blank">
    <img src="https://img.shields.io/badge/Supported%20by-IN--SPACe-blue?style=for-the-badge">
  </a>
</p>

---

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=30&center=true&vCenter=true&width=700&height=70&duration=4000&lines=Innovation+in+Every+Flight+🚀" />
</h1>
