# pushup-counter-arduino-nano-33-ble
Push-up counter using Arduino Nano 33 BLE and IMU sensor

# 🏋️ Push-Up Counter using Arduino Nano 33 BLE

## 📌 Project Overview
This project implements an **automatic push-up counter** using the **Arduino Nano 33 BLE**.  
It uses the **built-in IMU (accelerometer)** sensor to detect body movement during push-ups and
counts each correct repetition automatically.

This system eliminates manual counting and provides a **portable, low-cost, and accurate**
fitness monitoring solution.

## 🎯 Objectives
- To automatically count push-ups using motion sensors
- To avoid camera-based systems
- To build a wearable and portable fitness tracking device
- To ensure accurate counting using threshold-based logic


---

🧰 Hardware Requirements
- Arduino Nano 33 BLE
- USB cable
- Power source (USB / Battery)
- (Optional) OLED / LCD display
- (Optional) LED or Buzzer

---

🧠 Sensors Used
- IMU Sensor (Accelerometer)
  - Detects upward and downward motion of the body
  - Used to identify push-up movement accurately

---

⚙️ Working Principle
1. The Arduino Nano 33 BLE is attached to the user's arm or chest.
2. The accelerometer continuously reads motion data.
3. A **DOWN position** and **UP position** are detected using predefined threshold values.
4. One complete **DOWN → UP** motion is considered as **one push-up**.
5. The push-up count is incremented and displayed or sent to the UI.

---

🔁 Algorithm
1. Initialize IMU sensor  
2. Read accelerometer values continuously  
3. Detect DOWN position  
4. Detect UP position  
5. If DOWN → UP sequence is complete:  
   - Increment push-up count  
6. Display or transmit the count  

---

🖥️ Arduino Setup Instructions
1. Open **Arduino IDE**
2. Go to **File → Open**
3. Select the project folder inside `Arduino_Code`
4. Connect **Arduino Nano 33 BLE** using USB cable
5. Select **Board**: Arduino Nano 33 BLE
6. Select the correct **Port**
7. Click **Upload**

---

🌐 User Interface (UI)
- UI files are available in the `UI` folder
- Used to display push-up count or receive data via Bluetooth
- Can be extended to a mobile or web-based interface

---

🎥 Demo of Project Workflow
The complete working demonstration of the project is available on LinkedIn:

🔗 https://www.linkedin.com/posts/udaykumargudagudi_embeddedal-tinyml-edgelmpulse-activity-7407101561736171521-H5Zr?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEKPNMoBgdjfferKWzMeVVm6Ly7xnES9dJI

---

✅ Features
- Automatic push-up counting
- No camera required
- Portable and wearable design
- Low power consumption
- Accurate motion detection

---

📊 Applications
- Fitness tracking
- Home workout monitoring
- Gym exercise analysis
- Health and sports analytics

---

🚀 Future Enhancements
- Mobile app integration using Bluetooth
- Support for multiple exercises
- Accuracy improvement using gyroscope data
- Workout history and data logging

---

👤 Author
Udaykumar Gudagudi  
B.Tech – Computer Science Engineering (AI & ML)

---

📜 License
This project is for educational and learning purposes.

