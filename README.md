# Lena-Li - DE Final Capstone Project 
## Arduino Claw Machine Project Overview 

This project is a robust claw-machine built using Arduino, stepper motors, servo control, and a joystick input. It is fully functional and we focused on making the build durable and very user-friendly as it is designed for kids ages 5-11. This goal of this project is to donate it to BLAST, an afterschool program at Los Peñasquitos Elementary School that has parterned with Westview's Robotics Team - Option 16. We hope to provide the students with a fun reward for their hard work in engaging in FIRST Robotics. 

This claw machine is built around an Arduino Mega Board and controls multiple motors, a joystick, buttons, limit switches, and an LCD screen to deliver real-time feedback.

### Key Features:

X/Y gantry system & Z-direction pulley design for precise claw movement
- Servo-controlled claw for gripping objects
- Stepper motors for consistent X/Y movement and high-torque, repeatable positioning/angled turns
- Joystick and buttons for control of gantry & claw movement
- LCD display for messages such as INSERT COIN and GAME OVER
- Ensured safety using limit switches to prevent over-travel
- Ultrasonic Sensors to sense the coin being inserted

<p align="center">
  <img src="demo.gif" width="600"/>
</p>

---

## 🚀 Project Highlights

- 🎮 Real-time joystick control (X, Y, Z movement)
- ⚙️ Stepper-driven gantry system
- 🤖 Servo-controlled claw grip
- 💰 Coin acceptor + start button logic
- 🚫 Single-direction movement (arcade-accurate)
- 💡 LED game state indicators

---

## 📸 Demo

| Gameplay | Claw Mechanism |
|---------|----------------|
| ![gameplay](gameplay.jpg) | ![claw](claw.jpg) |

🎥 **Full Video Demo:** [Watch here](LINK)

---

## 🧠 How It Works

```text
Insert Coin → Press Start → Move Claw → Drop → Grab → Reset
