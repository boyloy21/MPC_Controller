## MPC_Controller
# Flow to Use This Code for simulation:
1. Step1: Install ROS2 Foxy
2. Step2: You must be connect bluetooth PC with PS4 or PS5
3. Step3: Run Commannd ros2 run joy joy_node
4. Step4: Run file ps4_control.py
5. Step5: You can choose one to run file simulation (mpc_mecanum_simv.py or omni_mpcSimV1.py)

## Flow to use on Real Robot
1. Component:
   - Board: STM32F103 2 Board, MINIPC or RaspberyPI 1,
   - Model: DC Motro encoder 4, OMNI Wheel 4, Base 1
   - Comunication : USBCAN, Module CAN
   - Sensor: Rotary ecnoder 2, IMU 1
2. Control:
   - PID on DC Motor
   - FeedBack Value from sensor
   - MPC control on Wheel Robot
   - Input Path Planing to Controller
# Result 
1. Mecanum Wheel Simulation:
   
https://github.com/user-attachments/assets/bcd77c0e-6e73-4fb5-bb47-eac2461ad74f

2. Omni Wheel Testing Hardware using Path Planning:

https://github.com/user-attachments/assets/f5ac5ce4-5a99-4d36-8f24-50d4fb5b557f
