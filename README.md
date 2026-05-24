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

`Programming Languages:` Arduino C/C++, Python

`Computer Vision & AI Model:` OpenCV, YOLOv8

`Development Environments:` Arduino IDE, VS Code

`Communication & Alert System:` Telegram Bot API

`Version Control & Repository:` GitHubTechnologies and Tools
     
# 🏗️ System Architecture


# ⚙️ Working Principle

1️⃣ Sensors continuously monitor infant conditions 👶

2️⃣ ESP32 reads temperature, humidity, sound, and wetness data ⚡

3️⃣ Webcam captures real-time baby video 🎥

4️⃣ YOLOv8 analyzes unsafe sleeping positions 🧠

5️⃣ Servo motor swings cradle automatically 🔄

6️⃣ Relay controls fan based on temperature 🌬️

7️⃣ Telegram bot sends instant alerts 📩

8️⃣ Parents monitor the baby remotely 📱

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

# 📤 Outputs

✅ 🌡️ High Temperature Alerts

✅ 💧 Diaper Wetness Alerts'

✅ 👶 Baby Cry Detection Alerts'

✅ 🛏️ Unsafe Sleep Position Alerts'

✅ 🌬️ Fan ON/OFF Status Alerts'

✅ 🔄 Automatic Cradle Swinging'

✅ 📩 Telegram Real-Time Notifications'

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

# 🚀 How to Run the Project
1️⃣ Clone the Repository
  
git clone https://github.com/your-username/AI-Enhanced-IoT-Cradle-Monitoring-System.git

2️⃣ Upload ESP32 Arduino Code

✅ Open Arduino IDE

✅ Install ESP32 Board Package

✅ Connect ESP32 Board

✅ Upload Arduino Code

3️⃣ Install Python Libraries
 
- `pip install ultralytics`
  
- `pip install opencv-python`
  
- `pip install numpy`

- `pip install pyserial`
  
4️⃣ Run YOLOv8 AI Monitoring

python yolov8_detection.py

🖼️ Output Screenshots

Add screenshots of:

📷 Hardware Setup
🔌 Circuit Connections
🧠 YOLOv8 Detection Output
📩 Telegram Alert Messages



Example:

📁 Images/
├── hardware_setup.png
├── circuit_diagram.png
├── yolov8_output.png
├── telegram_alert.png
└── fan_control_output.png
🎥 Output Video

Add the project demo video inside the Videos/ folder.

Example:

📁 Videos/
└── project_demo.mp4

You can upload the demo video to:

▶️ YouTube
☁️ Google Drive
🌐 GitHub Releases
💼 LinkedIn
🔮 Future Enhancements

🚑 Heartbeat Monitoring
🫁 Oxygen Level Monitoring
📱 Mobile Application Development
🗣️ Voice Assistant Integration
🧠 Edge AI Processing
😊 Facial Expression Analysis
🏥 Smart Healthcare Integration
☁️ Cloud Dashboard Integration

📜 License

This project is licensed under the MIT License 📄.

👩‍💻 Author

- Hazari Divyani

📚 References

1️⃣ ESP32 Official Documentation
2️⃣ YOLOv8 Documentation
3️⃣ OpenCV Documentation
4️⃣ Telegram Bot API Documentation
5️⃣ Arduino IDE Documentation
6️⃣ IEEE Research Papers on Smart Infant Monitoring

✅ Conclusion

The AI-Enhanced IoT Cradle Monitoring System with Predictive Infant Safety Alerts provides an intelligent and reliable infant monitoring solution using IoT 🌐, Artificial Intelligence , Machine Learning 🤖, and Computer Vision 👁️ technologies.

The integration of ESP32, sensors, relay-controlled fan system, SG90 servo motor, webcam monitoring, and YOLOv8 AI detection enables real-time monitoring and predictive infant safety analysis.

The system successfully:

✅ Detects baby crying
✅ Detects diaper wetness
✅ Monitors temperature and humidity
✅ Detects unsafe sleep positions
✅ Controls fan automatically
✅ Swings cradle automatically
✅ Sends instant Telegram alerts

This project demonstrates a smart healthcare solution that improves infant safety, reduces parental stress, and enables real-time remote monitoring for modern smart homes and healthcare systems.
