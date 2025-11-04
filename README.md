<!-- HEADER -->
<h1 align="center">🚀✨ Rocketry Avionics System ✨🚀</h1>
<h3 align="center">🛰️ Developed by <b>Team Sudarshan</b> | Under the <b>IN-SPACe Student Rocketry Initiative</b></h3>

<p align="center">
  <img src="https://media.giphy.com/media/mCRJDo24UvJMA/giphy.gif" width="130px" alt="Rocket Launch Animation">
</p>
![avionics_assembly](https://github.com/user-attachments/assets/11c89624-1df6-48f8-9244-b53ba96dbf42?raw=true)


<p align="center">
  <img src="https://img.shields.io/badge/Platform-Raspberry%20Pi%20Pico%202-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Designed%20with-EasyEDA-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Communication-XBee%203%20Pro%20%7C%20SIM800L-lightgreen?style=for-the-badge">
  <img src="https://img.shields.io/badge/Category-Rocketry%20Avionics-red?style=for-the-badge">
</p>

---

## 🌍 Overview  

The **Rocket Avionics System** is a compact, high-performance onboard electronics suite designed to power **student and experimental rockets**.  
Developed by **Team Sudarshan** under the **IN-SPACe initiative**, this system acts as the **central intelligence** of the rocket — seamlessly managing **data acquisition, telemetry, navigation, and event control** with precision and reliability.  

Engineered in **EasyEDA**, the design merges **microcontrollers, sensors, communication, and power management** into a single optimized PCB for real-world aerospace testing.

<p align="center">
  <img src="https://media.giphy.com/media/QB0L2Ap0NfjWv1eT8r/giphy.gif" width="250px" alt="Rocket Animation">
</p>

---

## ⚙️ Core Architecture  

### 🧠 Main Controllers  
- **Raspberry Pi Pico 2** – Primary flight computer executing mission logic and control algorithms  
- **Arduino Nano 33 BLE Sense** – Dedicated co-processor for sensor interfacing and data preprocessing  

---

### 📡 Communication & Navigation  
- **XBee 3 Pro** → Short-range telemetry and GCS communication  
- **SIM800L GSM** → Long-range data uplink for mission updates  
- **NavIC GPS** → Real-time positional and timing accuracy for flight tracking  

---

### 📊 Sensor Suite  
| Sensor | Function |
|---------|-----------|
| **BNO085 IMU** | Orientation and motion tracking |
| **BMP390** | Barometric pressure and altitude measurement |
| **INA219** | Power monitoring (voltage & current) |
| **MAX31856** | Thermocouple-based temperature sensing |
| **DS3231 RTC** | Precise real-time clock for timestamping |
| **SD Card Module** | Reliable onboard data logging |

<p align="center">
  <img src="https://media.giphy.com/media/LmNwrBhejkK9EFP504/giphy.gif" width="230px" alt="Data Flow Animation">
</p>

---

## 🔋 Power & Event Control  

- **Power Input:** 7.4V Li-Po Battery  
- **Regulated Outputs:** 5V & 3.3V for stable operation  
- **Relays & MOSFETs:** Safe triggering of pyro/separation events  
- **LED Indicators & Buzzer:** Instant system feedback for flight status  

<p align="center">
  <img src="https://media.giphy.com/media/fAnEC88LccN7a/giphy.gif" width="230px" alt="Power Animation">
</p>

---

## 🧩 Highlights  
✅ Compact & modular PCB design  
✅ Real-time telemetry and data logging  
✅ Dual-microcontroller redundancy  
✅ Fully NavIC-compatible for Indian aerospace research  
✅ Designed & simulated in EasyEDA for manufacturing precision  

---

