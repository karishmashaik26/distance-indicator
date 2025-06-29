# distance-indicator
# 📏 Ultrasonic Distance Visual Indicator with LEDs – Arduino Project

This project uses an HC-SR04 ultrasonic sensor to measure the distance of an object and lights up one of four LEDs based on that distance. Great for smart parking, obstacle alerting, or range visualization.

---

## 🧰 Components Required

- Arduino UNO
- HC-SR04 Ultrasonic Sensor
- 4 x LEDs (Red, Green, Yellow, White)
- 4 x 220Ω Resistors
- Jumper Wires & Breadboard

---

## 🔌 Wiring

| Component        | Arduino Pin |
|------------------|-------------|
| Ultrasonic Trig  | D9          |
| Ultrasonic Echo  | D10         |
| LED RED          | D13         |
| LED GREEN        | D12         |
| LED YELLOW       | D11         |
| LED WHITE        | D8          |

---

## 🎯 LED Behavior Based on Distance

| Distance (cm)    | LED ON       |
|------------------|--------------|
| `< 10`           | RED          |
| `10 - 20`        | GREEN        |
| `21 - 50`        | YELLOW       |
| `> 50`           | WHITE        |

---

## 📁 Files

- `code/distance_led_indicator.ino` — Main Arduino sketch

---

## 🔄 Applications

- Smart parking assistance  
- Obstacle visualization  
- Teaching tool for ultrasonic sensors  
- Range-based alerts

---
