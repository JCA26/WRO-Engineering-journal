WRO 2025 - Future Engineers Submission 

Team Name
Student Engineers

Team Members
- Jahmil Camacho – Vehicle Designer & Analyst  
- Angel Arocho – Coder & Tester

Age Group
16–17

Vehicle Name
CDC-05

Project Title
Autonomous LEGO-Based Car for Lap Completion

Season
WRO 2025

Project Description
Our project focuses on developing and programming an autonomous LEGO car that completes laps around a closed-loop track as quickly and accurately as possible. The robot is fully autonomous after start, prioritizing speed and control to avoid penalties from obstacle collisions. The car uses a combination of **color sensors**, **ultrasonic sensors**, and a **LEGO Spike Prime system** to detect its position, avoid collisions, and steer effectively through the course.

Table of Contents
a. Initial Research
b. Strategy and Design Planning
c. Mechanical Design
d. Electronics and Sensors
f. Challenges and Solutions

Objective:
Develop and program an autonomous LEGO-based car that completes laps around a predefined track as quickly and accurately as possible.
Key Rules from WRO 2025 Guide:
Robot must be fully autonomous after start.
The robot must complete laps around a closed circuit in under 3 minutes.
Speed and control are both important – penalties are given moving obstacles in the track.


Initial Research
What We Investigated:
•	Racing line techniques and cornering dynamics.
•	Drivetrain efficiency (2WD vs 4WD).
•	Vehicle size and weight efficiency.
•	LEGO-compatible sensor placement for optimal detection.
•	Components for the chassis of the vehicle.
Sources:
•	Previous WRO Future Engineers finals videos.
•	LEGO forums and GitHub for sample code.
•	YouTube (e.g., Roboriseit, TechBrick tutorials).

Strategy and Design Planning
Main Design Goals:
•	Maximize turning precision.
•	Smooth acceleration and steady speed control.
•	Minimize margin of error for sensor detection.
•	Consistent lap times with low variance.

Lap Optimization Ideas:
•	Interior wall detection for tight turning
•	Sensor feedback loops for steering adjustments.
•	Color detection for track awareness.

Mechanical Design
Chassis Design:
•	Custom low-profile LEGO chassis for low center of gravity.
•	Rear-wheel drive with large wheels for torque.
•	Front steering rack for precise movements.
•	Front Smaller wheels for precision.
Motors:
•	1x Medium Blue Servo Motor (54696 / 79818) in the front for vehicle steering.
•	1x Medium Azure SPIKE Primer Motor (54675 / 99085) in the rear for vehicle movement.
Key Innovations:
•	Changeable LEGO sensor mount for front and rear.
•	Lightweight LEGO Technic framework.
•	Swappable wheel sets for testing grip vs speed

Electronics and Sensors
Vehicle power source:
•	1x LEGO Spike V3 Large Hub
Sensors Used:
•	2x LEGO Color Sensors (color guide)
•	2x LEGO Ultrasonic Sensor (edge detection)
Sensor Placement Strategy:
•	Color sensors in the front facing forward and down 1 for front wall detection and 1 for ground color detection.
•	Ultrasonic Sensors for side wall detection.

Challenges and Solutions
Problem 1: Robot skidded out on sharp corners.
Fix: Reduced speed at corners.

Problem 2: Lap line detection would happen 50/50.
Fix: Adjusted color sensor position for better detection.

Problem 3: Vehicle stability was poor and would un align easily.
Fix: Added supports for wheels and front steering rack.

Demo Video

[Watch the Test Run on YouTube](https://youtu.be/ZN7BdKQKQTI)
