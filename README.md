<div align="center">
  <h1>🚀 Smart Noise Detection Device for Factory Workers 🏭</h1>
</div>

### 🚨 Protecting Hearing, One Factory at a Time! 
Industrial workplaces are notoriously loud! Heavy machinery produces noise pollution that regularly exceeds safe limits, putting workers' long-term hearing at risk. 
This project is an affordable, robust **Noise Sensing and Notification System** designed to keep industrial workers safe! 👷‍♂️

### ⚙️ How It Works
Powered by an **Arduino Uno** 🧠, this system constantly listens to ambient noise levels. If things get dangerously loud:
* 🔴 **Instant Alerts:** Bright LED indicators flash and a buzzer sounds off immediately!
* 📊 **Live Displays:** Noise levels are printed in real-time on a crisp OLED screen.
* 📱 **Mobile App:** Data is zapped via Bluetooth to a custom mobile app (built with MIT App Inventor), letting supervisors monitor noise graphs from afar!

### ✨ Key Features
* 🎤 **Continuous Monitoring:** Never misses a beat (or a dangerously loud crash).
* 📡 **Bluetooth Connectivity:** Wireless data streaming to Android devices.
* 💸 **Cost-Effective:** A high-utility safety solution that doesn't break the bank!

---

### 📖 Deep Dive Details

We will be going through the full setup and working principles of a crucial noise detection device designed specifically for the safety of factory workers! 🏭

## 👋 **Introduction**

Industrial workplaces often produce high levels of noise due to heavy machinery and equipment. Prolonged exposure to such noise can harm workers' hearing and affect their overall health and productivity. In India, studies have shown that noise pollution in many factories exceeds the safe limit prescribed by the Central Pollution Control Board (CPCB), putting workers at risk.

To ensure worker safety and improve monitoring, it's important to have a system that can detect high noise levels and alert employees in real-time. This project aims to develop a noise sensing and notification system using Arduino Uno. The system measures ambient noise levels, displays the values on an OLED screen, and alerts workers using LEDs and a buzzer when the noise exceeds a safe threshold. The data is also sent to a mobile app via Bluetooth, allowing supervisors to monitor noise levels through graphs and trigger alerts if necessary.

This system provides a low-cost, effective solution for noise monitoring in factories, helping improve occupational safety and awareness.

## ⚠️ **Problem Statement**
Excessive noise in industrial environments is a major health hazard that can lead to hearing loss, stress, and decreased concentration among workers. In many factories across India, there is no effective system to continuously monitor noise levels and alert workers when the noise crosses safe limits. This lack of real-time monitoring increases the risk of long-term hearing damage and reduces workplace safety.

There is a need for an affordable, easy-to-use system that can detect high noise levels, provide immediate alerts to employees, and allow supervisors to monitor the data remotely.

This project addresses this issue by developing a noise sensing and notification system using Arduino, which can detect noise levels, alert workers instantly, and send real-time data to a mobile application for remote monitoring.

## 💡 **Solution**
To solve the problem of **unsafe and hazardous noise levels** in factory environments, we have developed a Noise Sensing and Notification System using Arduino Uno, a noise sensor, Bluetooth communication, LED indicators, a buzzer, and a mobile application built using MIT App Inventor.

The system works by continuously measuring the surrounding noise using a noise sensor. The sensor readings are processed by the Arduino, which compares them against a predefined safe threshold. If the noise exceeds the limit:

A **bright red LED** is turned on instantly, and a buzzer is activated to immediately alert workers.

If the noise is within safe levels, a green LED remains on.

The noise value is displayed on a 0.96-inch OLED display for visual reference.

The Arduino also sends the noise data to a smartphone via the HC-05 Bluetooth module. The mobile app displays these values in real-time using a graph, allowing factory managers to monitor noise levels remotely. The app also includes a feature to directly call the manager from the alert screen if required.

This system offers a low-cost, portable, and real-time solution to ensure safer factory environments and better health protection for workers

## 🔌 **Components Used**
1. Arduino Uno – Main microcontroller board for processing sensor data and controlling output devices.

2. Noise Sensor Module – Detects ambient noise levels and sends analog values to Arduino.

3. HC-05 Bluetooth Module – Enables wireless communication between Arduino and the mobile app.

4. 0.96-inch I2C OLED Display (Blue) – Displays real-time noise values.

5. Red LED – Indicates high noise levels (alert condition).

6. Green LED – Indicates safe noise levels (normal condition).

7. Buzzer – Provides an audible alert when noise exceeds the set threshold.

8. Jumper Wires – For making connections between components.

9. Breadboard – Used for prototyping and connecting components without soldering.

10. Smartphone with MIT App Inventor App Installed – To display noise levels, graphs, and call the manager.

11. USB Cable for Arduino Uno – Used for programming and powering the board.

---

<div align="center">
  <h2><strong>👨‍💻 Connect with Me</strong></h2>
  <a href="https://github.com/Ashwin-Sahyadri-ECE022"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/ashwin-suresh-aa2573268"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:ashwinsuresh1122@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</div>
