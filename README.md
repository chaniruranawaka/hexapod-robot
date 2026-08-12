# Hexapod Robot

A custom-designed six-legged robotic platform developed as a foundation for future robotics research involving **ROS 2, computer vision, embedded control, and autonomous locomotion**.

The project is currently in the mechanical design and prototyping stage. The robot body and leg components were designed using SolidWorks and manufactured using 3D printing.

---

## Project Overview

The goal of this project is to develop a modular hexapod robot capable of supporting future:

- Autonomous locomotion
- Computer vision
- ROS 2 integration
- Embedded motor control
- Sensor integration
- Real-time robotics applications

The mechanical platform is being developed first, with software and control systems to be integrated progressively.

---

## Current Development Status

| Component | Status |
|---|---|
| Mechanical CAD design | Completed |
| SolidWorks modelling | Completed |
| STL preparation | Completed |
| 3D-printed prototype | Completed |
| Mechanical assembly | Completed |
| Electronics integration | Planned |
| Firmware | Planned |
| ROS 2 integration | Planned |
| Computer vision | Planned |
| Autonomous locomotion | Planned |

---

## Mechanical Design

The robot was completely designed using **SolidWorks**, including the main body and individual leg components.

### SolidWorks Assembly

The main assembly is available in:

```text
cad/solidworks/My HEXAPODE.SLDASM
```

Individual SolidWorks part files are available in:

```text
cad/solidworks/
```

### CAD Parts

The current design contains:

- Main robot body
- Leg components
- Multiple mechanical joints
- Modular leg structures
- 3D-printable components

---

## 3D-Printable Models

STL files exported from the CAD design are provided in:

```text
cad/stl/
```

Current printable components include:

```text
Leg Part1.STL
Leg Part2.STL
Leg Part3.STL
Leg Part4.STL
```

These files can be used for fabrication and further prototyping.

---

## Prototype

The designed components were manufactured using **3D printing** and assembled to verify the mechanical design and physical structure.

### Assembly Images

#### Assembly View 1

![Assembly View 3](images/assembly/Screenshot%202026-08-03%20130711.png)

#### Assembly View 2

![Assembly View 4](images/assembly/Screenshot%202026-08-03%20130728.png)

#### Assembly View 3

![Assembly View 6](images/assembly/Screenshot%202026-08-03%20130825.png)

---

## Repository Structure

```text
hexapod-robot/
│
├── cad/
│   ├── drawings/
│   ├── solidworks/
│   ├── source/
│   └── stl/
│
├── computer_vision/
│
├── docs/
│   ├── documentation/
│   ├── images/
│   │   ├── cad/
│   │   └── prototype/
│   └── schematics/
│
├── firmware/
│
├── hardware/
│
├── images/
│   └── assembly/
│
├── ros2/
│
├── simulation/
│
└── README.md
```

The repository structure is intentionally modular so that future software and hardware development can be added without restructuring the project.

---

## Planned Development

### Embedded Control

Future firmware development will include:

- Motor control
- Servo control
- Sensor interfacing
- Low-level real-time control
- Communication interfaces

The firmware will be maintained under:

```text
firmware/
```

### ROS 2

ROS 2 will be used as the robotics middleware for higher-level control and communication.

Planned functionality includes:

- Robot state management
- Locomotion control
- Sensor data processing
- Navigation
- Communication between robotics modules

ROS 2 packages will be maintained under:

```text
ros2/
```

### Computer Vision

A computer vision subsystem will be integrated into the robot for future perception and autonomous operation.

Planned capabilities include:

- Object detection
- Environment perception
- Target identification
- Visual feedback for autonomous control

Computer vision code will be maintained under:

```text
computer_vision/
```

### Simulation

A simulation environment will be developed to test robot mechanics and control algorithms before deployment to the physical platform.

Simulation files will be maintained under:

```text
simulation/
```

---

## Development Roadmap

```text
Mechanical CAD
      │
      ▼
3D Printing
      │
      ▼
Physical Prototype
      │
      ▼
Electronics Integration
      │
      ▼
Firmware Development
      │
      ▼
ROS 2 Integration
      │
      ▼
Computer Vision
      │
      ▼
Locomotion Control
      │
      ▼
Autonomous Hexapod
```

---

## Technologies

### Current

- SolidWorks
- 3D Printing
- STL
- Mechanical CAD

### Planned

- ROS 2
- Python
- C/C++
- Computer Vision
- Embedded Systems
- Motor Control
- Sensor Fusion
- Autonomous Robotics

---

## Project Status

**Status: Active Development**

The mechanical platform and initial prototype have been completed. The software, electronics, perception, and autonomous control systems are planned as the next stages of development.

---

## Future Work

Future development will focus on integrating the mechanical platform with electronics and intelligent control systems.

Major objectives include:

1. Electronics integration
2. Motor and actuator control
3. Embedded firmware
4. ROS 2 architecture
5. Computer vision
6. Sensor integration
7. Locomotion algorithms
8. Autonomous navigation
9. Simulation and testing
10. Full robotic system integration

---

## Author

**Chaniru Ranawaka**

BSc (Hons) Electronic and Telecommunication Engineering  
University of Moratuwa

---

## License

This project is currently under active development. Licensing information will be added in a future revision.
