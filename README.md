
LoopMIT ESP32 Sensor Codes
==========================

This repository houses the finalized ESP32 firmware codes developed for the LoopMIT Hyperloop Pod by the official Hyperloop team at MIT Manipal. These codes are integral to the pod's sensor systems, facilitating real-time data acquisition and communication.

🚀 Project Overview
-------------------

The LoopMIT Hyperloop Pod integrates a suite of sensors to monitor and control various subsystems. This repository contains the ESP32 microcontroller codes responsible for interfacing with these sensors, ensuring accurate data collection and transmission.

📁 Repository Structure
-----------------------

- ImuTempMLXBNO/  
  Code for interfacing with the Inertial Measurement Unit (IMU), temperature sensors, and the MLX90614 infrared temperature sensor.

- MainESP32Code/  
  The primary ESP32 firmware managing core sensor integrations and data handling.

- Relay_receiverCode/  
  Firmware to control and monitor relay modules within the pod's electrical systems.

- voltageSensor_receiverCode/  
  Code dedicated to reading and processing data from voltage sensors.

🛠️ Getting Started
------------------

### Prerequisites

- ESP32 Development Board
- Arduino IDE or PlatformIO
- Required sensor modules (IMU, MLX90614, voltage sensors, etc.)
- Required libraries installed in your IDE

### Installation

1. Clone the Repository  
   ```
   git clone https://github.com/YashChauhan-2303/LoopMIT-ESP32SensorCodes.git
   ```

2. Open the Desired Code Folder  
   Navigate to the specific sensor code directory you intend to work with.

3. Load the Code into Your IDE  
   Open the `.ino` or relevant files using Arduino IDE or your preferred development environment.

4. Configure the Code  
   Adjust pin configurations and sensor parameters as per your hardware setup.

5. Upload to ESP32  
   Connect your ESP32 board via USB and upload the code.

📌 Notes
--------

- Make sure your sensors are wired properly to the ESP32 board.
- Check that all required libraries are installed for your chosen sensors.
- Refer to the comments and README files (if available) in each subdirectory for sensor-specific setup.

🤝 Contributing
---------------

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.

📄 License
----------

This project is licensed under the MIT License. See the LICENSE file for details.

📬 Contact
----------

For inquiries or further information, please contact Yash Chauhan (yashchauhan2303@example.com).
