---
title: "EMG-Controlled Bionic Hand"
excerpt: "This custom-designed bionic hand operates using EMG signals, combining precision engineering and innovative bio-signal processing for enhanced prosthetic functionality."
header:
  image: /assets/img/Full_Assembly.jpg
  teaser: /assets/img/Assembly.jpg
gallery:
  - url: assets/img/Prototype.jpg
    image_path: assets/img/Prototype.jpg
    alt: "placeholder image 1"
  - url: assets/img/Circuitboard.jpg
    image_path: assets/img/Circuitboard.jpg
    alt: "placeholder image 2"
  - url: assets/img/Visual.png
    image_path: assets/img/Visual.png
    alt: "placeholder image 3"
---

This innovative prosthetic device replicates natural hand movements by converting EMG signals from muscle activity into precise mechanical motion. Powered by MyoWare EMG sensors, an Arduino microcontroller, and five servo motors, the bionic hand provides lifelike articulation and responsiveness. An OLED display enhances usability by offering real-time feedback on muscle signals and system performance. Combining advanced bio-signal processing, hardware design, and software development, this project demonstrates a functional and accessible solution for improving prosthetic technology.

### Purpose and Features
- **Purpose**: To develop a prosthetic hand that mimics natural hand movements using muscle activity data (EMG).
- **Key Features**:
  - EMG signal integration for real-time control.
  - Servo motor articulation for lifelike finger movement.
  - OLED display for feedback on muscle signals and system status.
  - Lightweight, customizable design with 3D-printed components.

---

### Parts List

#### Off-the-Shelf Components
| **Part**               | **Quantity** | **Description**                       |
|-------------------------|--------------|---------------------------------------|
| Arduino Uno            | 1            | Microcontroller for signal processing |
| MyoWare EMG Sensor Kit | 1            | Reads muscle activity signals         |
| Servo Motors           | 5            | Enables movement of fingers           |
| OLED Display           | 1            | Real-time system feedback             |

#### 3D-Printed Components
| **Part**          | **Material**     | **Purpose**               |
|--------------------|------------------|---------------------------|
| Hand Frame         | PLA             | Structure and durability  |
| Finger Joints      | PLA             | Articulating finger parts |
| Motor Mounts       | PLA             | Secures motors in place   |

---

### Arduino Code
The Arduino code processes EMG signals and controls the servos for finger movements. The code can be accessed here:  
[GitHub Repository - Arduino Code](https://github.com/JKevin101/Bionic_Hand)

---

### Interactive 3D Model
An interactive Fusion 360 model of the Bionic Hand assembly is available [here](#). *(Update with the actual link to the model if hosted online)*

---

### Operation
1. Wear the EMG sensors on the muscles controlling finger flexion and extension.
2. Connect the Arduino to power and upload the provided code.
3. Observe finger movements controlled by muscle activity detected by the EMG sensors.
4. Use the OLED display to monitor real-time feedback on signal processing.

---

### Conclusion
This project demonstrates how bio-signal processing and 3D-printed engineering can create accessible, innovative solutions for prosthetic development, advancing functionality and usability for individuals requiring assistive devices.
