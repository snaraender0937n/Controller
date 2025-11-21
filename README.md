# 🎮 ESP32 Game Controller (Wokwi + Arduino)

A virtual + hardware-ready **ESP32 game controller** featuring:

- Dual analog joysticks  
- 13 physical buttons  
- Wokwi simulation with mock BLE interface  
- Arduino firmware ready for real ESP32  
- Clean project structure  

This repository includes both **Wokwi simulation files** and **Arduino firmware**.

---

## 🚀 Features

- ESP32-based game controller  
- Two analog joysticks (X/Y axes)  
- 13 digital buttons using INPUT_PULLUP  
- Wokwi-compatible mock BLE implementation  
- Serial-only test firmware for debugging  
- Real BLE support when flashing to actual ESP32  

---

![Controller Diagram](docs/CONTROLLER.png)

---
## 🕹️ Button & Joystick Pin Mapping

### **Buttons**

| Button | GPIO |
|--------|------|
| X | 15 |
| O | 17 |
| Triangle | 4 |
| Square | 5 |
| R1 | 18 |
| R2 | 19 |
| L1 | 21 |
| L2 | 22 |
| Start | 23 |
| Select | 26 |
| PS | 25 |
| R3 | 33 |
| L3 | 32 |

### **Joysticks (Analog)**

| Axis | GPIO |
|------|------|
| Left X | 14 |
| Left Y | 27 |
| Right X | 12 |
| Right Y | 13 |
