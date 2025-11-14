 **ANTI-THEFT VEHICLE TRACKING SYSTEM**

This project presents a robust IoT-based solution to prevent vehicle theft and enable real-time tracking. 
By integrating GPS, GSM, and ESP32 microcontroller technologies, the system detects unauthorized activity 
and empowers vehicle owners to respond remotely.

 **Components**

 1. ESP32 Microcontroller
- Acts as the brain of the system.
- Handles data processing and communication.
- Built-in Wi-Fi enables real-time data transmission to cloud or mobile app.

 2. GPS Module
- Continuously receives satellite signals to determine the vehicle’s location.
- Provides latitude and longitude coordinates for tracking.

 3. Vibration Sensor
- Detects physical disturbances or unauthorized movement.
- Triggers alerts when suspicious activity is sensed.

 4. GSM Module
- Sends SMS alerts to the vehicle owner.
- Useful in areas with limited Wi-Fi connectivity.

5. Relay Module
- Controls the ignition or fuel supply system.
- Enables remote immobilization of the vehicle.

6. DC Motor
- Simulates engine or mechanical movement for testing.
- Demonstrates the effect of immobilization.

 7. Servo Motor
- Engages physical locking mechanisms like steering or door locks.
- Adds an extra layer of mechanical security.

 8. Buzzer
- Emits a loud alarm when theft is detected.
- Acts as a deterrent to intruders.

 9. Power Supply Unit
- Provides regulated voltage to all components.
- Includes transformer, rectifier, capacitor filter, and voltage regulator.

10. Arduino IDE
- Used for writing and uploading code to the ESP32.
- Supports serial monitoring and debugging.

 **Working Principle** 
The system uses a GPS module to track the vehicle's location and a vibration sensor to detect unauthorized movement. 
When suspicious activity is detected, the ESP32 microcontroller triggers a buzzer alarm and sends alerts to the owner via Wi-Fi or GSM. 
The owner can then remotely immobilize the vehicle using a relay and activate a servo motor to lock critical parts like the steering or doors. 
All data is logged for monitoring and recovery support.

 **Advantages**
- Real-Time Tracking: Continuously monitors vehicle location using GPS for instant updates.
- Theft Detection: Vibration sensor detects unauthorized movement or tampering.
- Remote Control: Owner can immobilize the vehicle and activate locks remotely.
- Instant Alerts: Sends notifications via buzzer and mobile app/SMS for quick response.
- Data Logging: Stores movement history for analysis and recovery support.
- Enhanced Security: Acts as a strong deterrent against theft attempts.
- Cost-Effective: Uses affordable components and open-source platforms.
- Scalable Design: Can be expanded for fleet management or integrated with cloud services.

**Applications**
- Personal Vehicle Security: Protects individual cars and bikes from theft with real-time tracking and remote control.
- Fleet Management: Enables logistics companies to monitor and manage multiple vehicles efficiently.
- Rental Services: Assists car and bike rental agencies in tracking usage and preventing unauthorized access.
- School and College Transport: Ensures safety and location tracking of buses and vans used for student transport.
- Emergency Response Vehicles: Helps track ambulances and fire trucks for faster dispatch and coordination.
- Government and Military Use: Secures official vehicles and supports location-based mission planning.





