<div align="center">
  <h1>🚦 Traffic Light System - PIC16F887 🚦</h1>
  <p>✨ A traffic light system simulation for a four-way intersection using <strong>PIC16F887</strong> microcontroller.</p>
  <p>Supports 3 flexible operating modes: automatic, manual control, and night warning.</p>

  <p>
    <img src="https://img.shields.io/badge/PIC16F887-Microcontroller-brightgreen?style=for-the-badge&logo=microchip&logoColor=white" alt="PIC16F887 Badge">
    <img src="https://img.shields.io/badge/Language-CCS%20C-blue?style=for-the-badge&logo=c&logoColor=white" alt="CCS C Badge">
    <img src="https://img.shields.io/badge/Simulation-Proteus-orange?style=for-the-badge&logo=proteus&logoColor=white" alt="Proteus Badge">
  </p>

---

  <p>
    <a href="#🚀-overview">Overview</a> •
    <a href="#📁-project-structure">Project Structure</a> •
    <a href="#🛠️-how-to-use">How to Use</a> •
    <a href="#⚙️-features">Features</a> •
    <a href="#🚩-real-product">Real Product</a>
  </p>

---
</div>

<br>

## 🚀 Overview

This is a **traffic light system simulation for a four-way intersection** using **PIC16F887 microcontroller**. The system supports **3 flexible operating modes** that can be selected using buttons or switches.

Each mode accurately simulates how real traffic lights work:

1. **Mode 1 - Automatic:** Red, yellow, and green lights cycle in sequence.
2. **Mode 2 - Manual Control:** Users press buttons to turn lights on and off manually.
3. **Mode 3 - Night Warning:** All 4 yellow lights blink continuously as a warning.

<br>

## 📁 Project Structure

```bash
Den_Giao_Thong_Nga_Tu/
│
├── Traffic_light.c          # CCS C source code
│          
├── Traffic_light.pdsprj     # Proteus simulation file
│  
└── README.md                # Project description
```
<br>

## 🛠️ How to Use

### 🔧 Required Software

1. CCS C Compiler – To compile the .c source code

2. Proteus Design Suite – To simulate the .pdsprj circuit

### 📥 Steps

1. Download the repository:

```bash
git clone https://github.com/LucPac/PIC16F887_Traffic_light.git
```

2. Open **Traffic_light.c** file with CCS C to view, edit, or compile the source code.

3. Open **Traffic_light.pdsprj** file with Proteus to simulate the circuit.

4. Select a mode and observe the traffic light changes in Proteus.

<br>

## ⚙️ Features

```bash
| Mode                 | Description                                                                |
| -------------------- | -------------------------------------------------------------------------- |
| 1 - Automatic        | Lights cycle through: red → green → yellow. Each has a preset time.       |
| 2 - Manual Control   | All lights are off. Users press individual buttons to turn lights on/off. |
| 3 - Night Warning    | All 4 yellow lights in all directions blink continuously.                 |
```

<br>

## 🚩 Real Product  

* PCB

![image](https://github.com/user-attachments/assets/c7a95654-681c-425e-acbe-62025cee1891)

![image](https://github.com/user-attachments/assets/a02374b4-9962-466d-985d-026dc2323736)

* Simulation Screenshot

![Screenshot (87)](https://github.com/user-attachments/assets/ab239cb8-e1cf-4113-8b71-a299691e1804)

* Simulation Video

[![image](https://github.com/user-attachments/assets/8d0833b3-2b20-427d-b9ea-355a20739084)](https://youtu.be/7rp6wgsRKR4)

<br>

---

<div align="center">
  <br>
  <p>Thank you for visiting! I hope this repository is helpful for your learning and research. 😊</p>
  </div>
