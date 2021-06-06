# Autopilot 🚘 🛣️
[![](https://img.shields.io/github/license/sourcerer-io/hall-of-fame.svg?colorB=ff0000)](https://github.com/akshaybahadur21/Autopilot/blob/master/LICENSE.txt)  [![](https://img.shields.io/badge/Akshay-Bahadur-brightgreen.svg?colorB=ff0000)](https://akshaybahadur.com)

This code helps in getting the steering angle of self driving car. 

## Inspiration 🗼

1) [Udacity Self driving car](https://github.com/udacity/CarND-Behavioral-Cloning-P3)
2) [End to End Learning for Self-Driving Cars](https://devblogs.nvidia.com/deep-learning-self-driving-cars/)

## Versions 🗽

1) [Autopilot Version 1](https://github.com/akshaybahadur21/Autopilot)
2) [Autopilot Version 2](https://github.com/akshaybahadur21/Autopilot/tree/master/Autopilot_V2)

## Code Requirements 🦄
You can install Conda for python which resolves all the dependencies for machine learning.

`pip install requirements.txt`

## Description 🏎️
An autonomous car (also known as a driverless car, self-driving car, and robotic car) is a vehicle that is capable of sensing its environment and navigating without human input. Autonomous cars combine a variety of techniques to perceive their surroundings, including radar, laser light, GPS, odometry, and computer vision. Advanced control systems interpret sensory information to identify appropriate navigation paths, as well as obstacles and relevant signage

## File Organization 🗄️

```shell
├── Autopilot Parent (Current Directory)
    ├── Autopilot
        ├── models 
        ├── resources
        ├── Trainer.py
        ├── DataLoader.py
        └── Main Application.py
    ├── Autopilot_V2
        ├── models 
        ├── resources
        ├── Trainer.py
        ├── DataLoader.py
        └── Main Application.py
    ├── LICENSE
    ├── requirements.txt
    └── readme.md
        
```

## Autopilot V1 (Udacity Dataset based on Udacity Simulator)
<img src="https://github.com/akshaybahadur21/BLOB/blob/master/final.gif">

## Autopilot V2 (NVIDIA Dataset based on real world)
<img src="https://github.com/akshaybahadur21/BLOB/blob/master/v2.gif">

## References 🔱
 
 - Mariusz Bojarski, Davide Del Testa, Daniel Dworakowski, Bernhard Firner, Beat Flepp, Prasoon Goyal, Lawrence D. Jackel, Mathew Monfort, Urs Muller, Jiakai Zhang, Xin Zhang, Jake Zhao, Karol Zieba. [End to End Learning for Self-Driving Cars](https://arxiv.org/abs/1604.07316)
 - [Behavioral Cloning Project](https://github.com/udacity/CarND-Behavioral-Cloning-P3) 
 - This implementation also took a lot of inspiration from the Sully Chen github repository: https://github.com/SullyChen/Autopilot-TensorFlow  
