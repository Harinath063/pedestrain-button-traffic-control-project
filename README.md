🚦 Advanced Smart Traffic Light Controller
📌 Project Overview

This project is an Advanced Smart Traffic Light Controller built using Arduino UNO.
It improves traditional traffic systems by adding:

🚗 Vehicle detection using IR sensor

🚶 Pedestrian crossing button

🔢 Pedestrian access limited to 25 uses per day

📟 I2C 16x2 LCD display for live status updates

🚨 Emergency-ready design concept

The system balances traffic efficiency and pedestrian safety.

🎯 Objectives

Automate traffic signal control

Reduce unnecessary traffic stoppage

Prevent misuse of pedestrian crossing

Display real-time crossing count

Demonstrate smart control system design

🧠 System Features
1️⃣ Vehicle Detection

IR sensor detects vehicle presence

Green signal duration increases when vehicles are detected

2️⃣ Pedestrian Button (Limited to 25 Uses)

Each press allows safe crossing

LCD displays usage count (e.g., 5/25)

After 25 uses:

Button becomes inactive

System continues normal operation

3️⃣ I2C LCD Display

Displays:

Remaining pedestrian accesses

Current usage count

“Limit Reached” message when maximum is exceeded

🔧 Components Used

Arduino UNO

Red, Yellow, Green LEDs

3 × 220Ω Resistors

1 × 10kΩ Pull-up Resistor

IR Sensor

Push Button

16x2 I2C LCD Display

Breadboard & Jumper Wires

🔌 Circuit Connections
LEDs

Red → Pin 13

Yellow → Pin 12

Green → Pin 11

IR Sensor

VCC → 5V

GND → GND

OUT → Pin 7

Push Button (Pull-Up Configuration)

One side → Pin 2

Other side → GND

10kΩ resistor → Between Pin 2 and 5V

I2C LCD

VCC → 5V

GND → GND

SDA → A4

SCL → A5

⚙️ How It Works

Traffic lights operate in normal sequence.

IR sensor adjusts green light timing based on vehicle presence.

When pedestrian button is pressed:

Red light turns ON

Crossing time is provided

LCD updates usage count

After 25 uses:

Button is disabled

LCD shows “Limit Reached”

System continues automatic traffic control

🧪 Testing (Tinkercad Simulation)

Start simulation

Press push button to simulate pedestrian request

Toggle IR sensor output to simulate vehicle detection

Observe LCD updates and LED behavior

🌍 Real-World Applications

School zones

Hospital areas

Smart city intersections

Controlled pedestrian crossings

🚨 Emergency Handling Concept

The pedestrian limit applies only to normal use.
In real-world systems, emergency override mechanisms are provided to ensure safety is never compromised.

📈 Future Improvements

Real-Time Clock (RTC) for daily reset

Emergency vehicle detection

IoT-based traffic monitoring

Cloud-based traffic analytics

👨‍💻 Author

V.Venkata Harinath.
Electronics & Communication Engineering
Arduino-Based Smart Control System Project
