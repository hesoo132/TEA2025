# 🎵 TEA2025 Stereo Amplifier  
*Simple Audio Amplifier Hardware Platform*

![Hero Image](docs/images/tea2025-amp.png)

---

## 🔎 Overview
This project implements a **stereo audio amplifier circuit** based on the **TEA2025 IC**.  
It takes low-level audio input signals (e.g., from a smartphone or MP3 player) and amplifies them to drive external speakers.  
The design was created as part of the course **“컴퓨터를 이용한 회로 설계 (15주차 과제)”**.

---

## 🔧 Hardware Features

| Component                  | Purpose                                                                 |
|----------------------------|-------------------------------------------------------------------------|
| **TEA2025 IC**             | Core dual-channel audio amplifier, supports stereo L/R channels        |
| **Power Supply (J1, C1, C2, LED)** | Provides stable DC input, filtering capacitors, and power indicator |
| **Audio Input (J2, J7, C5, C8)**   | Stereo input connectors with coupling capacitors to block DC offset |
| **Audio Output (J3, C12, C13)**    | Amplified output sent to external speakers via protection capacitors |
| **Feedback Capacitors (C6, C7)**   | Set amplifier gain and frequency response characteristics           |
| **Ripple Rejection (C10, C11)**    | Reduce noise from the power supply for cleaner audio                |
| **Indicator LED (D1, R1)**         | Visual indicator of power-on status                                 |

---

## 📸 Hardware Overview
| Schematic | PCB Preview |
|-----------|-------------|
| ![Schematic](docs/images/tea2025-schematic.png) | ![PCB](docs/images/tea2025-pcb.png) |

---

## ✅ Current Status
- [x] Schematic design completed  
- [x] Component selection & wiring verified  
- [ ] PCB layout (optional)  
- [ ] Hardware testing with speakers  

---

## 📑 References
- [TEA2025 Datasheet](https://www.alldatasheet.com/datasheet-pdf/pdf/23744/STMICROELECTRONICS/TEA2025.html)  
- Course: **컴퓨터를 이용한 회로 설계 – 15주차 과제**
