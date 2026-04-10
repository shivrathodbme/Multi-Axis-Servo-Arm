# 🤖 HexaArm: 6DOF Robotic Arm Controller

A DIY **6-degree-of-freedom (6DOF) robotic arm control system** using Arduino, servo motors, and joystick modules. This project provides real-time manual control of a robotic arm and serves as a foundation for advanced robotics applications.

---

## 📌 Features

* 🎮 Real-time control using joystick modules
* ⚙️ 6 independent axes (6 DOF)
* 🔌 Direct servo interfacing with Arduino
* 🧩 Modular and easy to expand
* 🛠️ Suitable for learning robotics and embedded systems

---

## 🧰 Hardware Requirements

* Arduino Uno (or compatible board)
* 6x Servo Motors (MG996R / SG90 or equivalent)
* 3x Joystick Modules
* External 5V Power Supply (high current recommended)
* Jumper wires
* Robotic arm structure (3D printed or assembled)

---

## 🔌 System Overview

* Each joystick provides 2-axis input → total 6 axes
* Analog signals from joysticks are read by Arduino
* Signals are mapped to servo angles (0°–180°)
* Each servo controls one joint of the robotic arm

---

## ⚠️ Important Considerations

* Do not power servos directly from the Arduino
* Use an external regulated 5V supply (≥5A recommended)
* Ensure common ground between Arduino and power supply
* Mechanical load should match servo torque capacity

---

## 💻 Working Principle

The Arduino continuously reads analog values from joystick modules.
These values are mapped into corresponding servo positions, allowing intuitive manual control of each joint in real time.

---

## 🧪 Applications

* Pick-and-place robotic systems
* Educational robotics platforms
* Automation prototypes
* Human-controlled manipulators

---

## 🚀 Future Enhancements

* Inverse Kinematics (position-based control)
* Wireless control (Bluetooth / WiFi)
* Motion recording and playback
* Integration with computer vision systems

---

## 📸 Preview

(Add circuit diagram and robot images here)

---

## 📂 Project Structure

```
HexaArm/
│── code/
│   └── hexa_arm.ino
│── images/
│── docs/
│── README.md
```

---

## 🤝 Contributing

Contributions are welcome. Feel free to fork and improve the project.

---

## 📜 License

This project is open-source and available for educational and personal use.

---

## 👤 Author

Shiva
Electronics & Robotics Enthusiast
