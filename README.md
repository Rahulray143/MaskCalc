# MaskCalc
MaskCalc is a dual-function application built using Raspberry Pi Pico. It starts as a normal calculator, but with a secret twist—entering a specific key unlocks a secure private mode protected by a password. The OLED screen and 4x4 keypad provide a complete embedded experience.
# 🛡️ MaskCalc: A Disguised Private App in Calculator Form

## 🔍 Overview

**MaskCalc** is a dual-function embedded application built using the **Raspberry Pi Pico**, a **4x4 Keypad**, and an **SSD1306 OLED Display**.  
It functions as a regular calculator — until you press a secret key to enter **Private Mode**, where a **password** is required to gain access.

🧠 Ideal for learning **embedded systems**, **MicroPython**, **user authentication**, and **multifunction device interfaces**.

---

## 🚀 Features

- 🧮 **Basic Calculator Mode**
- 🔐 **Password-Protected Private Mode**
- 🖥️ OLED display interface using `ssd1306.py`
- ⌨️ 4x4 Matrix Keypad support
- 🧾 Expression evaluation
- 🧊 Hacker-style “Access Granted” screen
- 🔄 Mode switching via keypad input

---

## 🧰 Hardware Requirements

| Component         | Description                     |
|------------------|---------------------------------|
| Raspberry Pi Pico| Microcontroller board           |
| OLED Display     | 0.96" I2C SSD1306 (128x64)      |
| Keypad           | 4x4 Matrix Keypad               |
| Jumper Wires     | Male-to-Male                    |
| Breadboard       | Standard size                   |

---

## 🧑‍💻 Software Requirements

- ✅ **Thonny IDE**
  - Install from: [https://thonny.org](https://thonny.org)
  - Set interpreter to **"MicroPython (Raspberry Pi Pico)"**
- 📦 Required Files:
  - `main.py` — Application logic
  - `ssd1306.py` — OLED driver

---

## 🔄 How It Works

### ➤ OLED Startup Display
1:CalculatorMode
2:SecurityCheck


### ➤ Mode 1 – Calculator
- Press `1` to enter calculator mode
- Use keys `0-9`, `+`, `-`, `*`, `/`, `=`, and `c` (clear)
- Results are shown on the OLED

### ➤ Mode 2 – Security (Private App)
- Press `2` to enter password mode
- Enter 4-digit password (default: `1122`)
- Input is hidden as `****`
- On correct password: hacker-style welcome screen
- On incorrect password: error message and reset

---

## 🧾 File Structure

