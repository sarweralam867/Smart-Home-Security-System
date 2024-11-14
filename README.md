# Smart-Home-Security-System
Smart Home Security System || Brac University || CSE360 : Computer Interfacing

### Group Information
- **Farhan Faruk**, ID: 20301137
- **H.M. Sarwer Alam**, ID: 20301224
- **Elham Nusrat**, ID: 18301265
- **Maruf Bin Murtaza**, ID: 23141042
- **Md Mahibul Haque**, ID: 20101503

- # Smart Home Security System

## Project Overview
The Smart Home Security System is an advanced, Arduino-based setup designed to enhance home safety by integrating various sensors and a Bluetooth module for remote monitoring. The system combines multiple sensors to detect intrusions, fire threats, and gas leaks, offering both real-time and remote security management.

## Key Components
- **Arduino Nano**: Acts as the central processing unit, controlling and coordinating the system.
- **PIR Sensor**: Detects motion and triggers alarms in case of movement within a monitored area.
- **Flame Sensor**: Detects fire or high temperature, providing early fire threat warnings.
- **MQ-2 Gas Sensor**: Monitors hazardous gases such as LPG, smoke, and carbon monoxide, ensuring safety from potential gas leaks.
- **HC-05 Bluetooth Module**: Allows for remote control and sends alerts to a smartphone for real-time monitoring.
- **Buzzer**: Emits sound alerts to notify individuals of security events like movement, fire, or gas leaks.
- **I2C LCD Display**: Displays the real-time status of the system, providing visual feedback on the security state.

## Features
- **Remote Monitoring**: The Bluetooth module enables smartphone connectivity, allowing users to receive notifications and control the system remotely.
- **Modular Design**: The system is designed to be easily expanded by adding more sensors for additional functionality.
- **Security Coverage**: Protects homes, rental properties, and businesses by detecting intrusions, gas leaks, and fires.
- **User-Friendly Interface**: The I2C LCD display and Bluetooth interface ensure easy interaction and access to system data.

## Project Purpose
This system provides comprehensive protection against common safety hazards such as unauthorized access, fires, and gas leaks. The integration of Bluetooth adds convenience by enabling mobile app-based monitoring and control, offering an accessible and user-friendly security solution.

## Installation Instructions
1. **Hardware Setup**:
   - Connect the Arduino Nano to the sensors (PIR, Flame, MQ-2, etc.) and the Bluetooth module.
   - Connect the I2C LCD and buzzer to the Arduino for feedback and alert systems.

2. **Software Setup**:
   - Upload the code to the Arduino using the Arduino IDE.
   - Pair the HC-05 Bluetooth module with a smartphone app to control and monitor the system.

3. **Testing**:
   - Trigger the sensors (motion, flame, gas) to test their functionality and ensure real-time alerts via the mobile app.

## Future Improvements
- **Additional Sensors**: Add sensors for water leakage, door/window sensors, or additional gas types for broader coverage.
- **Cloud Integration**: Integrate the system with a cloud service for remote access and monitoring


