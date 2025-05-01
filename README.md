# Autonomous Hospital Medicine Delivery Robot

My senior project at Atılım University: A partially autonomous robot for medicine delivery in hospitals.

## ✅ Implemented Features

- **Line following system** using 2 IR sensors and Arduino Uno
- **Directional motor control** via differential DC motor logic (4 motors)
- **Human detection and live streaming** using Raspberry Pi + Pi Camera
- **Web interface** to monitor the front view in real-time from a browser

## 🧠 How it Works

- Robot follows a black line using two IR sensors.  
- If the line drifts to one side, motors are adjusted to re-center it.  
- Raspberry Pi streams live footage and performs human detection.  
- The live feed is accessible via a local web server.

## ⚙️ Planned But Not Implemented (Yet)

- **Obstacle avoidance** using a sound/ultrasonic sensor (to be added in v2)
- **Remote manual control** in case of delivery issues (future work)
- **Full autonomous return path** and mission feedback

## 🗂 Folder Structure

- `/code` – Arduino and Raspberry Pi scripts
- `/media` – Images, video, and project photos
- `/docs` – Report, circuit diagrams, and notes

---

**Developed by Ataberk Karagözoğlu**  
Electrical & Electronics Engineer, Atılım University (2025)
