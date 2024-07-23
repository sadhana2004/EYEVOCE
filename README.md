# EYEVOCE

# Overview
The Object and Obstacle Recognition for the Blind project is designed to enhance the mobility and safety of visually impaired individuals by using an advanced assistive device. This device integrates an ultrasonic sensor with a voice module to provide real-time auditory feedback about the presence and proximity of objects and obstacles in the user’s environment.

# Components
1. Raspberry Pi Pico
2. Ultrasonic Sensors (HC-SR04)
3. Voice Module
4. External Speaker
5. Jumper Wires
6. USB Cables

![image](https://github.com/user-attachments/assets/543d8f83-a6c4-4ee6-a4ca-637e8a52d0d6)

# Working Flow
1. Power On the Device:
a) Connect the Raspberry Pi Pico to a power source using the USB cable.

3. Initialize Sensors and Modules:
a) The Raspberry Pi Pico starts up and initializes the ultrasonic sensors and voice module.
b) The ultrasonic sensors begin measuring distances to nearby objects.

4. Distance Measurement:
a) The ultrasonic sensors emit ultrasonic waves and measure the time it takes for the waves to return after hitting an object.
b) The Pico processes these measurements to calculate the distance between the sensor and the object.

5. Object Detection:
a) Based on the measured distance, the Pico determines if an object is within a predefined range.
b) If an object is detected within the range, the device triggers the voice module.

6. Auditory Feedback:
a) The voice module plays a pre-recorded message through the external speaker to alert the user of the object’s presence.
b) The message indicates the proximity of the object (e.g., “Object detected, be careful”).

7. Continuous Monitoring:
a) The device continuously monitors for nearby objects as the user moves.
b) It provides ongoing feedback to help the user navigate their environment safely.

8. Device Shutdown:
a) The device remains active until it is powered off or disconnected.

![image](https://github.com/user-attachments/assets/d8e95e6c-68e4-4aa4-8b16-a631cd532fb9)
![image](https://github.com/user-attachments/assets/65a80170-b8ae-4606-9739-fad7bd5530d6)
![image](https://github.com/user-attachments/assets/29962537-5696-42f8-8cde-98b9d16ee9d0)
![image](https://github.com/user-attachments/assets/9e64fa76-8700-461a-b8e6-58e7bb01df38)

# Results
![image](https://github.com/user-attachments/assets/cba9675c-4e71-4d32-9f2f-674a6943d9c7)
![image](https://github.com/user-attachments/assets/4828bea0-7fce-4745-84a2-17548c37f095)

# Conclusion
The Object and Obstacle Recognition for the Blind project successfully addresses a critical need for enhanced mobility and safety for visually impaired individuals. By integrating an ultrasonic sensor with a voice module, the device provides real-time auditory feedback, helping users navigate their environment and avoid obstacles more effectively.

# Future Scope
a) Multilingual Support: Add options to provide alerts in different languages.
b) Mobile Alerts: Develop a mobile app for real-time notifications.
c) Emotion Detection: Integrate technology to understand nearby people's emotions.
d) Facial Recognition: Use a camera to identify familiar faces.
