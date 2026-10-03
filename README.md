🦖 Chrome Dino Game Automation using Arduino

A fun Arduino-based automation project that makes the Chrome Dino automatically jump when an obstacle is detected.

This project combines an Arduino Uno, ultrasonic sensor, and servo motor to detect obstacles and physically press the Space key on the laptop.

Sometimes, you just build something because it's fun. 🚀

🎯 Project Overview

The Chrome Dino game normally requires the player to press Space whenever an obstacle appears.

In this project:

Obstacle → Ultrasonic Sensor → Arduino → Servo Motor → Space Key → Dino Jumps 🦖

The ultrasonic sensor continuously measures the distance to an approaching obstacle. When the obstacle enters the defined detection range, the Arduino activates the servo motor, which moves to press the laptop's Space key.

✨ Features
🦖 Automatic Chrome Dino jumping
📡 Ultrasonic obstacle detection
🤖 Servo-controlled Space key
🔌 Arduino-based control
⚡ Real-time obstacle response
🛠️ Simple and beginner-friendly hardware setup
🎮 Built mainly for experimentation and fun
🔧 Hardware Required
Component	Quantity
Arduino Uno	1
HC-SR04 Ultrasonic Sensor	1
SG90 Servo Motor	1
Breadboard	1
Jumper Wires	As required
USB Cable	1
⚙️ Working Principle
The HC-SR04 ultrasonic sensor measures the distance to objects in front of it.
Arduino continuously reads the sensor data.
When an obstacle is detected within the predefined distance:
Arduino sends a command to the servo.
The servo moves toward the Space key.
The key is physically pressed.
The Chrome Dino jumps over the obstacle.
The servo returns to its original position and waits for the next obstacle.
System Flow
        🦖 Chrome Dino
              ↑
        Space Key Press
              ↑
        🤖 Servo Motor
              ↑
          Arduino Uno
              ↑
     📡 Ultrasonic Sensor
              ↑
       🚧 Obstacle
🧩 Software
Arduino IDE
Arduino C/C++
Google Chrome
Chrome Dino Game
Required Library
#include <Servo.h>

The Servo library is generally included with the Arduino IDE.

🚀 Getting Started
1. Connect the Hardware

Connect the ultrasonic sensor and servo motor to the Arduino according to the pin configuration used in the Arduino sketch.

2. Upload the Code

Open the .ino file in Arduino IDE and upload it to the Arduino Uno.

3. Open Chrome Dino

Open Chrome and start the Dino game.

You can use:

chrome://dino
4. Position the Servo

Place the servo so that its arm can physically press the Space key.

5. Start the Experiment

Place an obstacle in front of the ultrasonic sensor and observe the servo response.

📁 Repository Structure
Chrome-Dino-Arduino/
│
├── Chrome_Dino_Arduino.ino
├── README.md
└── images/
    └── project-setup.jpg
🎥 Demo

Add your project demonstration video here:

▶️ Watch the Demo Video

💻 Source Code

The complete Arduino code is available in this repository.

🔗 GitHub Repository

🧠 What I Learned

This project helped me experiment with:

Arduino programming
Ultrasonic distance measurement
Servo motor control
Sensor-based automation
Hardware-software interaction
Real-time decision making
Physical computer interaction
🎯 Purpose

This project isn't intended to solve a major real-world problem.

It was built purely for fun, experimentation, and learning.

Not every project has to be a startup idea, hackathon project, or resume project.

Sometimes you just want to ask:

"Can I make this work?"

And then build it. 😄

📌 Disclaimer

This is an experimental DIY project. The servo physically interacts with a laptop keyboard, so proper positioning and careful testing are recommended to avoid damaging the keyboard.

👨‍💻 Author

Sarthak Dewangan

Built with Arduino, curiosity, and a little bit of fun. 🦖⚙️

⭐ If you found this project interesting, feel free to star the repository!
