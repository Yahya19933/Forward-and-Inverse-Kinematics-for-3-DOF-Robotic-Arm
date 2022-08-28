# Forward-and-Inverse-Kinematics-for-3-DOF-Robotic-Arm
Forward and inverse kinematics motion for 3 DOF robotic arm


Connected 3 servo motors to Arduino to build a robotic arm to create two functions which are forward kinematics and inverse kinematics

## Forward kinematics function
**Forward Kinematics** is to get the co-ordinate(s) of the end effector from given angles of all joints
requires all lengths of links and angles 
The output shows x,y. and Total angle  
by using the below equations and writing them as code in Arduino

![Firest eq forword](https://latex.codecogs.com/gif.latex?X%20%3D%20L_%7B1%7D%20%5Ccos%20%28%5CTheta_%7B1%7D%29%20&plus;%20L_%7B2%7D%20%5Ccos%20%28%5CTheta_%7B1%7D%20&plus;%20%5CTheta_%7B2%7D%29%20&plus;%20L_%7B3%7D%20%5Ccos%20%28%5CTheta_%7B1%7D%20&plus;%20%5CTheta_%7B2%7D%20&plus;%20%5CTheta_%7B3%7D%29)

![Second eq Forword](https://latex.codecogs.com/gif.latex?Y%20%3D%20L_%7B1%7D%20%5Csin%20%28%5CTheta_%7B1%7D%29%20&plus;%20L_%7B2%7D%20%5Csin%28%5CTheta_%7B1%7D%20&plus;%20%5CTheta_%7B2%7D%29%20&plus;%20L_%7B3%7D%20%5Csin%20%28%5CTheta_%7B1%7D%20&plus;%20%5CTheta_%7B2%7D%20&plus;%20%5CTheta_%7B3%7D%29)

![third eq Forword](https://latex.codecogs.com/gif.latex?%5CTheta%20%3D%20%5CTheta_%7B1%7D%20&plus;%20%5CTheta_%7B2%7D%20&plus;%20%5CTheta_%7B3%7D)


## Inverse kinematics function
**Inverse Kinematics** is to get all joints angle from given co-ordinate(s)
requires all lengths of links and x,y, and Total angle 
The output shows all angles  
by using the below equations and writing them as code in Arduino
