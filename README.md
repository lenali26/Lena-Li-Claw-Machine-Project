# Lena Li - DE Final Capstone Project 
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
## Team Members
This project was completed as a collaboration between:

- Lena Li @lenali26 (me) 
- Claire Zhu @clairezzhu (me)
- Nora Dunn @norad4309

All team members contributed to research, design, testing, and coding of the Arduino Claw Machine.

---
## Bill of Materials 

| Component              | Quantity | Notes / Source                                 |
|------------------------|----------|-----------------------------------------------|
| Arduino Mega 2560      | 1        | Needed for sufficient I/O pins               |
| 16x2 LCD Screen        | 1        | Displays messages to user                     |
| NEMA 17 Stepper Motors | 4        | 2 for Y-axis, 1 X-axis, 1 Z-axis             |
| Servo Motor            | 1        | Controls claw grip                            |
| Joystick               | 1        | Controls X/Y gantry                           |
| Buttons                | 3       | Start, coin, Z-axis control                   |
| Limit Switches         | 3       | For X/Y/Z travel limits                       |
| TIP-120 Transistors    | 18       | Control motor power safely                    |
| Resistors              | 18       | For transistor bases                           |
| Breadboard & Jumper Wires | N/A   | For testbed and prototyping                   |
| Power Supply           | N/A      | 5V logic for Arduino, separate motor supply  |
| Motor Driver           | 5      | 4 for Stepper motors and 1 for Servo motor, controls the speed, direction, and torque  |
| Potentiometer           | 1      | Controls the voltage supply to the motor  |

*Additional smaller electrical components and shafts were used for the assembly* 

---
## Motor & Component Testing
All motors and components were tested individually before integration:

| Component      | Test Summary          | Observations                                      |
|----------------|---------------------|--------------------------------------------------|
| Servo Motor    | Potentiometer control | Smooth motion, precise positioning, limited torque |
| Stepper Motor  | Step-based control    | High torque, precise positioning, slower for continuous motion |
| Joystick       | Analog X/Y           | Controlled gantry axes successfully             |
| Limit Switches | Digital input        | Effectively stops motion and prevents over-travel |

*Test codes are in the `setup/` folder.*

---
## Demo

| Gameplay | Claw Mechanism |
|---------|----------------|
| ![gameplay](gameplay.jpg) | ![claw](claw.jpg) |

**Full Video Demo:** [Watch here](LINK)

*Still in progress*

---
## Code
Full code is still in progress. The completed project code will be available in the `code/` folder when done. 

## Wiring Diagram



## Assembly Plan
1. Create the CAD design of the claw machine on Fusion360
/assets/images/ -- (Insert Image here)
3. Build testbed for individual components (Arduino Uno (for initial testing), motors, joystick, switches, etc)
4. Assemble X/Y gantry system and mount motors
5. Assemble Claw using pulley design for Z-Axis movement 
6. Wire motors through TIP-120 transistors to Arduino Mega and finalize the ports for the code
7. Connect all electrical components
8. Verify shared ground connections and separate motor power supply
9. Upload Arduino code and test individual subsystems
10. Integrate all code and run full test
11. If parts of the test is not working smoothly, troubleshoot until successful!


## References
- Arduino Mega: https://store.arduino.cc/products/arduino-mega-2560-rev3
- LCD: https://www.youtube.com/watch?v=s_-nIgo71_w&t=121s
- Servo: https://www.youtube.com/watch?v=8-w_8izUO38
- Stepper: https://www.youtube.com/watch?v=7spK_BkMJys&t=360s
- Button: https://www.youtube.com/watch?v=VPGRqML_v0w
- Joystick: https://www.youtube.com/watch?v=vo7SbVhW3pE&t=336s
- Limit Switches: https://www.youtube.com/watch?v=6wuInF9Yw08
