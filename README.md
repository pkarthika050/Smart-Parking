📌 Project Overview

Smart Car Parking System is an IoT-based project developed using ESP32 and simulated in Wokwi.
The system monitors the availability of parking slots using ultrasonic sensors and indicates the status using LEDs.
It helps identify whether a parking slot is vacant or occupied in real time.

🛠️ Components Used

ESP32 Microcontroller

Ultrasonic Sensors (HC-SR04) – 4 units

Red & Green LEDs (for slot indication)

Wokwi Simulator

⚙️ Working Principle

Each parking slot is assigned one ultrasonic sensor.

The sensor measures the distance between the sensor and the vehicle.

If the measured distance is:

≥ 10 cm → Slot is Vacant

Green LED ON

Red LED OFF

< 10 cm → Slot is Occupied

Red LED ON

Green LED OFF

ESP32 continuously reads sensor data and updates the LED status.

Parking status values (p1, p2, p3, p4) are generated and can be sent to an external application (Bluetooth logic placeholder included).

💻 Software & Technologies

Arduino C/C++

ESP32 Board

Wokwi Online Simulator

📊 Features

Real-time parking slot detection

Visual indication using LEDs

Supports 4 parking slots

Serial Monitor output for debugging

Scalable for mobile/app integration

🧪 Simulation

The complete project is simulated in Wokwi, and the working output is verified through:

LED status changes

Serial monitor distance values

📂 Repository Contents

ESP32 source code

Circuit connections (Wokwi)

Screenshots / screen recording of working simulation
