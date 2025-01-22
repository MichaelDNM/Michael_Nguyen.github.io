---
title: "EMG-Controlled Bionic Hand"
excerpt: "This custom-designed bionic hand operates using EMG signals, combining precision engineering and innovative bio-signal processing for enhanced prosthetic functionality."
header:
  image: /assets/img/Full_Assembly.jpg
  teaser: /assets/img/Full_Assembly.jpg
gallery:
  - url: /assets/img/Full_Assembly.jpg
    image_path: /assets/img/Full_Assembly.jpg
    alt: "placeholder image 1"
  - url: /assets/img/Circuitboard.jpg
    image_path: /assets/img/Circuitboard.jpg
    alt: "placeholder image 2"
  - url: /assets/img/Visual.png
    image_path: /assets/img/Visual.png
    alt: "placeholder image 3"
---

This innovative prosthetic device replicates natural hand movements by converting EMG signals from muscle activity into precise mechanical motion. Powered by MyoWare EMG sensors, an Arduino microcontroller, and five servo motors, the bionic hand provides lifelike articulation and responsiveness. An OLED display enhances usability by offering real-time feedback on muscle signals and system performance. Combining advanced bio-signal processing, hardware design, and software development, this project demonstrates a functional and accessible solution for improving prosthetic technology.

{% include gallery caption="This is a sample gallery to go along with this case study." %}

### Purpose and Features
- **Purpose**: To develop a prosthetic hand that mimics natural hand movements using muscle activity data (EMG).
- **Key Features**:
  - EMG signal integration for real-time control.
  - Servo motor articulation for lifelike finger movement.
  - OLED display for feedback on muscle signals and system status.
  - Lightweight, customizable design with 3D-printed components.

---
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
| OLED Display           | 1            | Provides real-time system feedback    |

#### 3D-Printed Components

| **Part**          | **Material** | **Purpose**                     |
|--------------------|--------------|---------------------------------|
| Hand Frame         | PLA          | Provides structure and durability |
| Finger Joints      | PLA          | Articulating finger components  |
| Motor Mounts       | PLA          | Secures motors in place         |

---

### Arduino Code
The Arduino code processes EMG signals and controls the servos for finger movements. The code can be accessed here:  
[GitHub Repository - Arduino Code](https://github.com/JKevin101/Bionic_Hand)

---

### Interactive 3D Model
An interactive Fusion 360 model of the Bionic Hand assembly is available [here](#). *(Update with the actual link to the model if hosted online)*

---

### Operation

1. **Hardware Setup**:
   - **EMG Sensor Placement**: Attach the MyoWare EMG sensors to the target muscle groups responsible for hand movements. Ensure proper skin contact for accurate signal detection.
   - **Circuit Assembly**: Connect the EMG sensors, servo motors, and OLED display to the Arduino board as per the provided circuit diagram in your [GitHub repository](https://github.com/JKevin101/Bionic_Hand).

2. **Software Setup**:
   - **Arduino IDE**: Download and install the [Arduino IDE](https://www.arduino.cc/en/software/).
   - **Library Installation**: Within the Arduino IDE, install the necessary libraries:
     - `Servo.h` for controlling the servo motors.
     - `Wire.h`, `Adafruit_GFX.h`, and `Adafruit_SSD1306.h` for handling the OLED display.
   - **Code Upload**: Open the Arduino code from your [GitHub repository](https://github.com/JKevin101/Bionic_Hand) and upload it to the Arduino board.

3. **System Calibration**:
   - **Power On**: Supply power to the Arduino board.
   - **Signal Monitoring**: Observe the OLED display for real-time feedback on EMG signal strength and system status.
   - **Threshold Adjustment**: If necessary, adjust the EMG signal thresholds in the code to match the user's muscle signal strength for optimal performance.

4. **Operation**:
   - **Muscle Activation**: Flex and extend the muscles where the EMG sensors are placed.
   - **Hand Movement**: The bionic hand should mimic the user's muscle movements in real time, providing lifelike articulation.

---

### Conclusion
This project demonstrates how bio-signal processing and 3D-printed engineering can create accessible, innovative solutions for prosthetic development, advancing functionality and usability for individuals requiring assistive devices.
