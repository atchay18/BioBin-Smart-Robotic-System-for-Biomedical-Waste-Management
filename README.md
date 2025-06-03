# BioBin-Smart-Robotic-System-for-Biomedical-Waste-Management

An AI-powered, mobile robotic system designed to detect, classify, and safely segregate biomedical waste like syringes and cotton using computer vision and embedded systems.

🚀Project Overview
---------------------------------------------------------------------------------------------------------------
BioBin is a smart biomedical waste segregation robot developed to automate the handling of hazardous waste in hospitals. It integrates YOLOv8-based object detection, Raspberry Pi, Arduino-controlled robotic arm, and ultrasonic sensor-based navigation to detect and sort medical waste into color-coded bins, minimizing human exposure and improving hospital hygiene.

💡Key Features
---------------------------------------------------------------------------------------------------------------
➦ YOLOv8 Real-Time Detection of syringes and cotton
➦ Arduino-based Robotic Arm for pick and place operation
➦ Raspberry Pi Integration with USB camera and relay control
➦ Autonomous Navigation using ultrasonic sensors
➦ Dual Battery System for separate motor and servo power
➦ UART Serial Communication between Pi and Arduino
➦ SDG Alignment: Health, Safety, Innovation

🎯 How It Works
---------------------------------------------------------------------------------------------------------------
✔️The camera captures a real-time image of the waste item.
✔️YOLOv8 detects whether the object is a syringe or cotton.
✔️Raspberry Pi sends a signal to Arduino via UART.
✔️Arduino controls the servo-based robotic arm to pick and sort the item into the correct bin.
✔️Ultrasonic sensors monitor obstacles, enabling safe navigation.
✔️DC motors move the robot, powered and managed through relay control.


📦System Architecture
---------------------------------------------------------------------------------------------------------------
Camera → Raspberry Pi (YOLOv8) → Serial Communication → Arduino → Servo Motors
             ↓                                     ↓
        Object Detection                    Robotic Arm Control
             ↓                                     ↓
     Ultrasonic Sensors → Navigation       Relay Modules → Motor Drive

📌Results
---------------------------------------------------------------------------------------------------------------
➛Accurate classification of biomedical waste in real-time
➛Safe and autonomous sorting into appropriate bins
➛Reduced human contact and biohazard risk
