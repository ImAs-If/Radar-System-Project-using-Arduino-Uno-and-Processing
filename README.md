## Arduino Radar System

A simple radar system built with **Arduino Uno**, an **HC-SR04 Ultrasonic Sensor**, and a **Servo Motor**, visualized using a **Processing IDE GUI**. The radar scans objects in front of it and displays their position on a radar-like interface.

## 📌 Features

* 180° scanning using a servo motor
* Object distance detection with ultrasonic sensor
* Real-time visualization in Processing GUI
* Displays object angle and distance in cm

## 🛠️ Components Used

* Arduino Uno
* HC-SR04 Ultrasonic Sensor
* SG90 Servo Motor
* Jumper Wires & Breadboard
* PC with Processing IDE installed

## 📂 Project Structure

```
Arduino-Radar-System/
│── arduino_code/
│   └── radar_system.ino
│
│── processing_code/
│   └── radar_visualization.pde
│
│── README.md
│── LICENSE
│── .gitignore
```

## ⚙️ Setup & Usage

1. **Arduino Side**

   * Upload the Arduino sketch (`radar_system.ino`) to your Arduino Uno.
   * Connect the Ultrasonic Sensor (Trig → D10, Echo → D11) and Servo Motor (PWM → D12).

2. **Processing Side**

   * Open `radar_visualization.pde` in Processing IDE.
   * Set the correct **COM port** in the code (`myPort = new Serial(this, "COM3", 9600);`).
   * Run the Processing sketch to see the radar interface.

## 🎮 Demo Output

* The radar scans from 0° to 180°.
* Objects within **40 cm** are displayed as red dots/lines.
* The interface shows angle, distance, and detection status.

## 📜 License


---
