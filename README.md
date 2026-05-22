# AI-Enhanced-IoT-Cradle-Monitoring-System-with-Predictive-Infant-Safety-Alerts-
The AI-Enhanced IoT Cradle Monitoring System with Predictive Infant Safety Alerts is a smart infant monitoring system using ESP32, sensors, YOLOv8, and Telegram alerts. It detects baby crying, wetness, unsafe sleeping positions, and controls fan and cradle movement automatically for infant safety.

# 📖 Project Overview

The AI-Enhanced IoT Cradle Monitoring System with Predictive Infant Safety Alerts is a smart infant healthcare monitoring system developed using IoT 🌐, Artificial Intelligence 🧠, Machine Learning 🤖, and Computer Vision 👁️ technologies.

This project continuously monitors infant safety conditions such as:

🌡️ Temperature

💧 Humidity

👶 Baby Cry Detection

🛏️ Baby Diaper Wetness Detection

🧠 Unsafe Sleep Position Detection

🌬️ Automatic Fan Control

The system uses an ESP32 ⚡ microcontroller connected with sensors, a relay module, SG90 servo motor, and a webcam for real-time monitoring and predictive safety alerts.

📩 Real-time alerts are sent through a Telegram Bot directly to parents or caregivers.

# 🎯 Objectives

✅ Develop a smart IoT-based infant monitoring system

✅ Monitor baby temperature and humidity in real time 

✅ Detect baby crying using sound sensors 

✅ Detect diaper wetness using rain sensors 

✅ Detect unsafe sleep positions using AI 

✅ Automatically control fan using relay module 

✅ Swing cradle using SG90 servo motor 

✅ Send real-time Telegram alerts 

✅ Reduce manual infant monitoring effort 

# 🛠️ Technologies and Tools

- ## Hardware Components
  
1. ESP32 Microcontroller
 
2. DHT11 Temperature & Humidity Sensor
     
3. Sound Sensor
     
4. Rain Sensor
     
5. SG90 Servo Motor
     
6. Relay Module
      
7. DC Toy Fan
     
8. USB Webcam
     
9. Jumper Wires
      
10. Breadboard
  
## 💻 Software Tools

1. Arduino IDE
     
2. Python
     
3. OpenCV
     
4. YOLOv8
     
5. Telegram Bot API
     
6. VS Code
     
7. 🌐 GitHub
     
# 🏗️ System Architecture

```
🌡️ DHT11 Sensor
🎤 Sound Sensor
💧 Rain Sensor
        ↓
      ⚡ ESP32
        ↓
🌐 Wi-Fi Communication
        ↓
📩 Telegram Bot Alerts
        ↓
📱 Parent Mobile

📷 Webcam
        ↓
🧠 YOLOv8 AI Detection
        ↓
🛏️ Unsafe Sleep Position Detection
```

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

## 📥 Input Device	🎯 Purpose
- 🌡️ DHT11 Sensor	Temperature & Humidity Monitoring
- 🎤 Sound Sensor	Baby Cry Detection
- 💧 Rain Sensor	Diaper Wetness Detection
- 📷 Webcam	Unsafe Sleep Position Detection
- 🔌 Connections
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

'Relay COM' → External Power Positive

- 7️⃣ 📷 Webcam Connections

'USB Webcam' → Laptop USB Port

# 📤 Outputs

'✅ 🌡️ High Temperature Alerts'

'✅ 💧 Diaper Wetness Alerts'

'✅ 👶 Baby Cry Detection Alerts'

'✅ 🛏️ Unsafe Sleep Position Alerts'

'✅ 🌬️ Fan ON/OFF Status Alerts'

'✅ 🔄 Automatic Cradle Swinging'

'✅ 📩 Telegram Real-Time Notifications'

# 📂 Project File Structure
'''
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
'''
# 🚀 How to Run the Project
- 1️⃣ Clone the Repository
  
git clone https://github.com/your-username/AI-Enhanced-IoT-Cradle-Monitoring-System.git

- 2️⃣ 'Install Python Libraries'
 
      'pip install ultralytics'
  
      'pip install opencv-python'
  
      'pip install numpy'

      'pip install pyserial'
  
- 3️⃣ Upload ESP32 Arduino Code

'✅ Open Arduino IDE'

'✅ Install ESP32 Board Package'

✅ Connect ESP32 Board'
✅ Upload Arduino Code

4️⃣ Run YOLOv8 AI Monitoring
python yolov8_detection.py
🖼️ Output Screenshots

Add screenshots of:

📷 Hardware Setup
🔌 Circuit Connections
🧠 YOLOv8 Detection Output
📩 Telegram Alert Messages
🌬️ Fan ON/OFF Alerts
🔄 Servo Motor Cradle Swinging

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

✨ Your Name

📚 References

1️⃣ ESP32 Official Documentation
2️⃣ YOLOv8 Documentation
3️⃣ OpenCV Documentation
4️⃣ Telegram Bot API Documentation
5️⃣ Arduino IDE Documentation
6️⃣ IEEE Research Papers on Smart Infant Monitoring

✅ Conclusion

The AI-Enhanced IoT Cradle Monitoring System with Predictive Infant Safety Alerts provides an intelligent and reliable infant monitoring solution using IoT 🌐, Artificial Intelligence 🧠, Machine Learning 🤖, and Computer Vision 👁️ technologies.

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
