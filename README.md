# Robotic Lawn Mower
This is a robot designed to autonomously mow the lawn. It is designed to run for long periods of time using relatively limited power. 
# Physical robot
The physical robot is built from a frame of wooden dowels and 3d printed parts. 
<br><br>
![20260111_144508](https://github.com/user-attachments/assets/983bf687-1229-44f4-a241-bf4570cc3ea0)
![20260111_144538](https://github.com/user-attachments/assets/5e23acdd-5ce0-4fab-83df-959c551a329b)
![20260111_144620](https://github.com/user-attachments/assets/fef5b158-7fcd-4d57-b78b-62d85352ecaf)


# Software plans
The robot will be controlled via a Xiao with a ESP32-c3 microprocessor. I have started working on a state machine in rust using the type state pattern to ensure safety for the embed software. An old linux converted PC will act as the server calculating the path for the robot utilizing either camera or gps data.
