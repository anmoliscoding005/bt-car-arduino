
# Bluetooth Controlled Car using Arduino and HC-05

This project demonstrates how to build a Bluetooth-controlled robotic car using Arduino, L293D motor driver shield, and HC-05 Bluetooth module.

## 🧰 Components Used
- Arduino UNO
- L293D Motor Driver Shield
- 4 DC Motors
- HC-05 Bluetooth Module
- Android phone with BT Car App
- Power supply (4 x 1.5V batteries)

## 🔌 Circuit Connections
- L293D Shield is mounted directly on Arduino UNO.
- HC-05 Bluetooth Module connected to:
  - VCC → 5V
  - GND → GND
  - TX → Digital Pin 11
  - RX → Digital Pin 10 (via voltage divider)

## 📲 BT Car App Commands
- **F** – Forward
- **B** – Backward
- **L** – Left Turn (Long)
- **R** – Right Turn (Long)
- **G** – Left Turn (Short)
- **I** – Right Turn (Short)
- **S** – Stop

## ⏱ Motion Control
Each command moves the car for a fixed short duration (like 500 ms or 100 ms) and stops automatically.

## 💻 Arduino Code
The code is available in `bt_car.ino`.
