# 💡 Arduino LED and Pushbutton Project

This simple Arduino project involves controlling three LEDs using three pushbuttons. Each button corresponds to a specific LED. Pressing the button turns the LED on, and releasing it turns the LED off.

---

## 📦 Project Overview

The project demonstrates basic interactions with pushbuttons and LEDs using an **Arduino**. When a button is pressed, the corresponding LED lights up, and it turns off when the button is released. This is a great project for learning how to interface buttons and LEDs with an Arduino microcontroller.

---

## 🧰 Components Needed

- **1 x Arduino Uno** (or any compatible Arduino board)
- **3 x LEDs** (preferably different colors)
- **3 x Pushbuttons**
- **3 x 220Ω Resistors** (for LEDs)
- **3 x 10kΩ Resistors** (for pull-down resistors on buttons)
- **Jumper wires**
- **Breadboard**

---

## 🔌 Circuit Diagram

- **LEDs**: Connect each LED's anode (long leg) to one of the Arduino digital pins (e.g., 2, 3, 4). Connect each cathode (short leg) through a **220Ω resistor** to ground (GND).
- **Pushbuttons**: Connect each pushbutton to a digital pin (e.g., 5, 6, 7) and ground. Use a **10kΩ pull-down resistor** to ensure the button state reads correctly.
- Connect **GND** to the common ground.

---



