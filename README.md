# 🤖 VEX Robotics — Autonomous Navigation

An autonomous robot built with VEX V5 that can traverse through a predefined map using sensors and programmed navigation logic. Built as a team project, leading a group of 4.

---

## 🎥 Demo

https://github.com/karankhullar2006/vex-robotics-autonomous/raw/main/VEX_Robotics_Side_Project.mp4

> Robot autonomously navigating through a map defined by black lines on a white surface.

---

## 🔧 How It Works

1. The robot is placed at the starting position on the map
2. Onboard sensors detect the black line boundaries of the map
3. The robot uses programmed navigation logic to traverse the map autonomously
4. Motor controls adjust in real time to keep the robot on the correct path
5. The robot completes the map without any manual input

---

## 🛠️ Technologies Used

| Component | Technology |
|---|---|
| Robot platform | VEX V5 |
| Programming language | Python |
| Navigation logic | Autonomous line following algorithm |
| Motor control | VEX V5 motor API |
| Sensors | VEX V5 vision/line sensors |

---

## 🧠 System Architecture

```
[Line Sensors] → [VEX V5 Brain] → [Drive Motors]
                      ↓
              [Python Navigation Logic]
         (reads sensor data, calculates
          direction, controls motors)
```

- **Sensors** continuously read the map boundaries
- **Python logic** processes sensor input and determines motor commands
- **Motors** adjust speed and direction in real time to navigate the map

---

## 👨‍💻 My Role

- Worked in a team of 4 through the full design and development process
- Wrote the autonomous navigation logic in Python
- Coordinated hardware assembly and software development across the team
- Debugged sensor readings and motor calibration during testing

---

## 📚 Key Learnings

- Autonomous systems programming with Python
- Real-time sensor input processing and motor control
- PID-style navigation logic for smooth path following
- Team coordination and task delegation across hardware and software roles

---

## 🔩 Hardware Components

- VEX V5 Brain
- VEX V5 Drive Motors
- VEX Line Tracking Sensors
- VEX V5 Robot Chassis

---

## 🏫 Context

Built as part of the Engineering Club at St. Marcellinus Secondary School. This project focused on autonomous navigation — a core concept in robotics and automotive systems such as Ford's driver assistance and self-driving features.
