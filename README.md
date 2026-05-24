# AI-Enhanced-IoT-Cradle-Monitoring-System-with-Predictive-Infant-Safety-Alerts-
# 📖 Project Overview
The AI-Enhanced IoT Cradle Monitoring System is a smart infant safety solution using ESP32, sensors, OpenCV, and YOLOv8 for real-time monitoring. The system detects baby crying, diaper wetness, unsafe sleeping positions, and controls cradle movement and fan operation automatically while sending instant Telegram alerts to parents in real time daily.

# 🎯 Objectives

1. To develop an AI-Enhanced IoT-Based Cradle Monitoring System for intelligent infant safety and monitoring.
   
2. To detect baby activities and unsafe sleep positions using sensors, webcam monitoring, and YOLOv8-based AI detection.
   
3. To provide real-time alerts and automated safety responses through Telegram Bot notifications and smart hardware control.

# Technologies & Tools Used

`Microcontroller:` ESP32

`Sensors:`

- DHT11 Temperature & Humidity Sensor
  
- Sound Sensor
  
- Rain Sensor

`Hardware Components:`

- SG90 Servo Motor
  
- Relay Module
  
- DC Toy Fan
  
- USB Webcam
  
- Jumper Wires
  
- Breadboard

`Programming Languages:` Arduino C++, Python

`Computer Vision & AI Model:` OpenCV, YOLOv8

`Development Environments:` Arduino IDE, VS Code

`Communication & Alert System:` Telegram Bot API

`Version Control & Repository:` GitHubTechnologies and Tools

# 📥 Inputs
  
1️⃣ 🌡️ DHT11 Sensor Connections

`VCC` → 3.3V (or 5V)

`GND` → GND

`DATA` → GPIO 4 (DHTPIN)

2️⃣ 🎤 Sound Sensor Connections

`VCC` → 3.3V

`GND` → GND

`OUT` → GPIO 34 (SOUND_SENSOR_PIN)

3️⃣ 💧 Rain Sensor Connections

`VCC` → 3.3V

`GND` → GND

`AO (Analog OUT)` → GPIO 35 (RAIN_SENSOR_PIN)

4️⃣ 🔄 SG90 Servo Motor Connections

`Red Wire (VCC)` → 5V

`Brown Wire (GND)` → GND

`Orange Wire (Signal)` → GPIO 13 (SERVO_PIN)

5️⃣ ⚡ Relay Module Connections

`VCC` → 5V

`GND` → GND

`IN` → GPIO 26 (RELAY_PIN)

6️⃣ 🌬️ DC Toy Fan Connections

`Fan Positive` → Relay NO

`Fan Negative` → GND

`Relay COM` → External Power Positive

7️⃣ 📷 Webcam Connections

`USB Webcam` → Laptop USB Port

# ⚙️Working Principle

The AI-Enhanced IoT Cradle Monitoring System continuously monitors the infant’s safety and surrounding environmental conditions using multiple sensors connected to the ESP32 microcontroller. The temperature, humidity, sound, and wetness sensors collect real-time data from the cradle environment. A webcam captures live video of the infant, and the YOLOv8-based machine learning model analyzes the video feed to detect unsafe sleeping positions or unusual movements. Based on the sensor readings, the system automatically controls the cradle swinging mechanism using a servo motor and regulates the fan through a relay module whenever the temperature exceeds the predefined limit. In critical situations such as abnormal temperature, excessive crying, or unsafe sleeping posture, instant alert notifications are sent to parents through a Telegram bot, enabling remote monitoring and immediate response for improved infant safety.

# Block Diagram

<img width="956" height="579" alt="Screenshot 2026-04-01 145441" src="https://github.com/user-attachments/assets/df58770a-dca8-4d0c-9ba4-976e056100f1" />

# Circuit Diagram

<img width="578" height="315" alt="CircuitD_Major" src="https://github.com/user-attachments/assets/4563600e-2575-40f2-9d59-a4db0139b648" />

# Hardware Connection

<img width="578" height="349" alt="HardwareC_Major" src="https://github.com/user-attachments/assets/c5cc3890-d992-48d6-a065-91036a9dce92" />

# 🏗️System Architecture Flow Diagram

<img width="1025" height="673" alt="Screenshot 2026-04-01 162216" src="https://github.com/user-attachments/assets/61648323-a27e-4334-bfdd-988ce4fbb460" />

# 🚀 How to Run the Project

1️⃣ Upload ESP32 Arduino Code

✅ Open Arduino IDE

✅ Install ESP32 Board Package

✅ Connect ESP32 Board

✅ Upload Arduino Code

2️⃣ Install Python Libraries
 
- `pip install ultralytics`
  
- `pip install opencv-python`
  
- `pip install numpy`

- `pip install pyserial`
  
3️⃣ Run YOLOv8 AI Monitoring

`python yolov8_detection.py`

# 📤 Outputs

## 1. Detection Of Safe and Unsafe Sleep Positions Using Roboflow

<img width="901" height="1600" alt="Detection Of Safe  Sleep Position Using Roboflow" src="https://github.com/user-attachments/assets/14dcd453-0729-47d5-aedd-8c94394f022d" /> <img width="941" height="1600" alt="Detection Of Unsafe Sleep Positions Using Roboflow" src="https://github.com/user-attachments/assets/7ce1916f-b043-4d2f-84f0-df2b1b78ea40" />

## 2. Real-Time Baby Safe Sleep Position Detection Using Web Camera

<img width="1222" height="835" alt="realtime safe" src="https://github.com/user-attachments/assets/41223a7c-ca5e-4027-b646-03ecdf3d6ed0" />

## 3. Real-Time Baby Unsafe Sleep Position Detection Using Web Camera

<img width="1363" height="956" alt="realtime unsafe" src="https://github.com/user-attachments/assets/be655715-23a9-4394-8231-1500ea0d9b65" />

## 4. Real-Time Alerts using Telegram Bot

<img width="540" height="1202" alt="WhatsApp Image 2026-02-03 at 12 27 11 PM (1)" src="https://github.com/user-attachments/assets/eb614ac7-17e2-45fa-992c-208de09fad8d" />
<img width="540" height="1202" alt="WhatsApp Image 2026-02-03 at 12 27 11 PM" src="https://github.com/user-attachments/assets/b2bf240c-fbbb-45f8-97c6-33049ec753b7" />
<img width="1024" height="1536" alt="Baby status alerts in Telegram chat" src="https://github.com/user-attachments/assets/064a68c6-847d-497b-b336-573231c66e4e" />

# 📂 Project File Structure
```
AI-Enhanced-IoT-Cradle-Monitoring-System/
│
├── 📁 Arduino_Code/
│   └── esp32_cradle_monitoring.ino
│
├── 📁 Python_AI_Code/
│   └── yolov8_detection.py
│
├── 📁 Dataset/
│
├── 📁 Documentation/
│   └── project_report.pdf
│
├── 📁 Images/
│   ├── system_architecture.png
│   ├── circuit_diagram.png
│   ├── output1.png
│   └── output2.png
│
├── 📁 Videos/
│   └── project_demo.mp4
│
├── 📄 README.md
├── 📄 requirements.txt
└── 📄 LICENSE
```
# Future Scope

`Addition of health monitoring sensors such as heartbeat and oxygen sensors`

`Cloud storage for maintaining infant monitoring history and analytics`

`Implementation of advanced AI models for improved behavior analysis`

`Integration with smart home automation systems`

✅ Conclusion

The AI-Enhanced IoT Cradle Monitoring System with Predictive Infant Safety Alerts successfully detects unsafe infant sleeping positions and environmental risks using YOLOv8 and IoT sensors. The system provides real-time alerts and automatic cradle movement for timely and effective infant safety monitoring. By integrating Artificial Intelligence, Machine Learning, and IoT technologies, the project enhances infant safety, supports remote monitoring, and reduces parental stress through continuous real-time monitoring and alert mechanisms.

📜 License

This project is licensed under the MIT License 📄.

👩‍💻 Author

`Hazari Divyani`
