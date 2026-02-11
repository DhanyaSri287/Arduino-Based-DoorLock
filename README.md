# Arduino-Based-DoorLock System  
### Keypad + LCD + Servo Based Password Protection

A secure electronic lock system built using **Arduino**, a **4x4 Matrix Keypad**, **16x2 LCD (I2C)**, and a **Servo Motor**.  
The system allows users to enter a password via keypad. If the password is correct, the servo unlocks the door. If incorrect, access is denied.

---

## 📌 Features

- 🔒 Password-protected access system  
- 📟 LCD display feedback (Enter Password / Access Granted / Access Denied)  
- ⚙️ Servo motor locking mechanism  
- 🔔 Buzzer alert for wrong password  
- 🛠 Easy to customize password  
- 💻 Written in Arduino C++  

---

## 🛠️ Components Required

- Arduino Uno / Nano  
- 4x4 Matrix Keypad  
- 16x2 LCD Display  
- I2C Module for LCD  
- SG90 Servo Motor  
- Buzzer  
- Breadboard  
- Jumper Wires  

---

## 🔌 Circuit Connections
![Circuit Diagram](Circuit.jpeg)

### LCD (I2C)
- VCC → 5V  
- GND → GND  
- SDA → A4  
- SCL → A5  

### Keypad
- Connect to Digital Pins (Example: D2–D9)

### Servo
- Signal → D10  
- VCC → 5V  
- GND → GND  

### Buzzer
- Positive → Digital Pin (Example: D11)  
- Negative → GND  

⚠️ Ensure all grounds are connected together.

---


## 💻 Software Requirements

- Arduino IDE  
- Required Libraries:
  - `Keypad.h`
  - `LiquidCrystal_I2C.h`
  - `Servo.h`

Install libraries from:

Sketch → Include Library → Manage Libraries

---

## 🚀 Installation

```bash
git clone https://github.com/your-username/arduino-secure-lock.git
cd arduino-secure-lock
