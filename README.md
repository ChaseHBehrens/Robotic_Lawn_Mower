# Robotic Lawn Mower
This is a robot designed to autonomously mow the lawn. It is designed to run for long periods of time using relatively limited power. 
# Physical robot
The physical robot is built from a frame of wooden dowels and 3d printed parts. 
<br><br>
<img src="https://github.com/user-attachments/assets/5b3f8606-1957-4d40-8131-41c14cbaa34c" width="300" />
<img src="https://github.com/user-attachments/assets/d6b28023-d424-4709-94c3-72246693a95c" width="300" />

# Software plans
The robot will be controlled via a Xiao with a ESP32-c3 microprocessor. I have started working on a state machine in rust using the type state pattern to ensure safety for the embed software. An old linux converted PC will act as the server calculating the path for the robot utilizing either camera or gps data.
