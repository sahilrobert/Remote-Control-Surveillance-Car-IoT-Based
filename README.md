# 🚗📷 Remote Control Surveillance Car (IoT Project)

A smart, Wi-Fi-enabled surveillance car built using NodeMCU (ESP8266), ESP32-CAM, and L298N motor driver. This project integrates real-time video streaming with remote control capabilities, making it ideal for home security, remote inspection, or educational robotics demonstrations.

---

## 📌 Features

- 🚘 Remote control (forward, backward, left, right, turn)
- 📶 Wi-Fi Access Point mode (no router required)
- 📷 Live video streaming via ESP32-CAM
- 🎮 Browser-based control interface
- 🔧 Modular design (easy to expand and customize)

---

## 🧰 Hardware Components

| Component          | Quantity |
|-------------------|----------|
| NodeMCU ESP8266   | 1        |
| ESP32-CAM         | 1        |
| L298N Motor Driver| 1        |
| DC Motors         | 4        |
| Chassis + Wheels  | 1 set    |
| Jumper Wires      | As needed|
| Power Source      | Battery or USB |
| Breadboard (optional) | 1    |

---

## 📁 Project Structure


---

## 🛠️ Setup Instructions

### 🔧 Programming NodeMCU (Motor Control)

1. Install **Arduino IDE** and the **ESP8266 board package**.
2. Connect your NodeMCU via USB.
3. Open `car_controller.ino` from `nodemcu_code/`.
4. Upload it to the NodeMCU.
5. Connect to Wi-Fi network: `NodeMCU Car`
6. In your browser, go to `192.168.4.1/?State=F` (or use `L`, `R`, `B`, `S`, etc.)

### 🎥 Programming ESP32-CAM (Video Streaming)

1. Install **ESP32 board package** in Arduino IDE.
2. Select board: `AI Thinker ESP32-CAM`.
3. Connect ESP32-CAM using FTDI programmer.
4. Open `camera_stream.ino` from `esp32cam_code/`.
5. Upload the sketch and monitor Serial Output.
6. Access the live stream via printed IP (usually `192.168.x.x`).

---

## 🎮 Control Commands

| Command | Action           |
|---------|------------------|
| `F`     | Move Forward      |
| `B`     | Move Backward     |
| `L`     | Turn Left         |
| `R`     | Turn Right        |
| `I`     | Slight Forward Right |
| `G`     | Slight Forward Left  |
| `J`     | Slight Backward Right|
| `H`     | Slight Backward Left |
| `S`     | Stop              |
| `0-9`   | Adjust Speed (400–1023) |

---

## 📸 Output

![Demo Car](media/demo.gif)

---

## ✅ Applications

- Home and property surveillance
- Search and rescue missions
- Wildlife monitoring
- Industrial inspections
- Robotics and IoT education

---

## 📚 References

- NodeMCU documentation: https://nodemcu.readthedocs.io/
- ESP32-CAM camera setup: https://randomnerdtutorials.com/esp32-cam-video-streaming-web-server-camera-home-assistant/
- L298N motor control basics

---

## 👨‍💻 Authors

- **Sahil Robert** (R22EI049)

42nd Semester, B.Tech CSE (IoT & Cybersecurity)  
REVA University, Bengaluru



