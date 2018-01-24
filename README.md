# Self Driving RC Car
## Introduction
Making self driving car project built on toy RC car with deep learning approach.

## System Configuration
### Hardware
#### Mobile Platform
* 1/10 scale RC-car (TRAXXAS SUMMIT, E-MAXX)
* 1/5 scale RC-car
#### LIDAR
* [Sweep scanning LIDAR](http://scanse.io/)
* [RPLIDAR A2](https://www.dfrobot.com/product-1461.html)
#### CAMERA
* USB3 Camera
* [Stereolabs ZED Camera](https://www.stereolabs.com/)
#### Processing Unit
* [Nuvo-5095GC](http://www.neousys-tech.com/en/product/application/gpu-computing/nuvo-5095gc-gpu-computer)
* [Nvidia TX2](https://developer.nvidia.com/embedded/buy/jetson-tx2)
* mini-ITX + GPU
#### GPS/IMU
* [SparkFun 9DoF Razor IMU M0](https://www.sparkfun.com/products/14001)
* [NovAtel SPAN-IGM-A1](https://www.novatel.com/products/span-gnss-inertial-systems/span-combined-systems/span-igm-a1/)
#### Etc
* MOCAT Battery Pack SK-NB30 30000mAh 
* Eth Router
#### Flight Controller
* Pixhawk 

### Software
- [ROS](http://www.ros.org/)
- [Tensorflow](https://www.tensorflow.org/)/[Keras](https://keras.io/)
- [OpenCV](https://github.com/jaeoh2/installOpenCVUbuntu14.04)
- [AutoRally Platform](https://github.com/AutoRally/autorally)
#### Simulator
- [Udacity Self-driving car Simulator](https://github.com/udacity/self-driving-car-sim)
- [TORCS-keras](https://github.com/yanpanlau/DDPG-Keras-Torcs)
- [CARLA](https://seattle.github.com/carla-simulator/carla)
- [AirSim](https://seattle.github.com/carla-simulator/carla)

### Dataset
- [Kitti](http://www.cvlibs.net/datasets/kitti/index.php)
- [Stanford Track Collection](http://cs.stanford.edu/people/teichman/stc/)

## References
- http://www.jetsonhacks.com/category/robotics/jetson-racecar/
- https://github.com/ApolloAuto/apollo/blob/master/docs/quickstart/apollo_1_0_hardware_system_installation_guide.md
- https://github.com/mit-racecar
- https://github.com/topics/autonomous-vehicles
### Papers
- [Multi-View 3D Object Detection Network for Autonomous Driving](https://arxiv.org/pdf/1611.07759.pdf)
- [MobileNet](https://arxiv.org/pdf/1704.04861.pdf)
- [LIDAR-based 3D Object Perception](https://pdfs.semanticscholar.org/2c45/03c72ba7f53f3385859bd5e6311c58e73905.pdf)
- [End-to-end Driving via Conditional Imitation Learning](https://arxiv.org/pdf/1710.02410.pdf)
