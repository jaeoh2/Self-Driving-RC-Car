# Self Driving RC Car
## Introduction
Making self driving car project built on toy RC car with deep learning approach.
Tested in Microsoft [AirSim](https://github.com/Microsoft/AirSim).
Implemented in scale RC car.

## System Configuration
### Hardware
#### Mobile Platform
* 1/8 scale RC-car
* 1/5 scale RC-car (HPI Baja 5SC)
#### LIDAR
* [Sweep scanning LIDAR](http://scanse.io/)
* [RPLIDAR A2:$319](https://www.dfrobot.com/product-1461.html) 
#### CAMERA
* USB3 Camera
* [Stereolabs ZED Camera:$499](https://www.stereolabs.com/)
* [RealSense d415:$149](https://click.intel.com/intelr-realsensetm-depth-camera-d415.html)
#### Processing Unit
* [Nuvo-5095GC](http://www.neousys-tech.com/en/product/application/gpu-computing/nuvo-5095gc-gpu-computer)
* [Nvidia TX2](https://developer.nvidia.com/embedded/buy/jetson-tx2)
* Custom PC  
  * core-i3
  * Gtx-1050ti
  * ssd 128G
  * DDR4 8G
  * mini-ITX
#### GPS/IMU
* [SparkFun 9DoF Razor IMU M0](https://www.sparkfun.com/products/14001)
* [NovAtel SPAN-IGM-A1](https://www.novatel.com/products/span-gnss-inertial-systems/span-combined-systems/span-igm-a1/)
* Microstrain 3DM-GX4-25 IMU
#### PSU
* [M4-ATX CAR PC PSU](http://www.mini-box.com/M4-ATX)
* DC/DC Converter (3.3v, 5v out)
* 
#### Battery
* MOCAT Battery Pack SK-NB30 30000mAh 
* 5,000~6,000 mAh 14v Battery Pack
* 10,000 ~ 20,000 mAh 22v Battery Pack
#### Flight Controller
* Pixhawk 

### Software
- [ROS](http://www.ros.org/)
- [Tensorflow](https://www.tensorflow.org/)/[Keras](https://keras.io/)
- [OpenCV](https://github.com/jaeoh2/installOpenCVUbuntu14.04)
- [AutoRally Platform](https://github.com/AutoRally/autorally)
#### Simulator
- [AirSim](https://seattle.github.com/carla-simulator/carla)
- [Udacity Self-driving car Simulator](https://github.com/udacity/self-driving-car-sim)
- [TORCS-keras](https://github.com/yanpanlau/DDPG-Keras-Torcs)
- [CARLA](https://seattle.github.com/carla-simulator/carla)

### Dataset
- [AirSim Tutorial Dataset](https://aka.ms/AirSimTutorialDataset)
- [Kitti](http://www.cvlibs.net/datasets/kitti/index.php)
- [Stanford Track Collection](http://cs.stanford.edu/people/teichman/stc/)

## References
- https://github.com/Microsoft/AutonomousDrivingCookbook
- http://www.jetsonhacks.com/category/robotics/jetson-racecar/
- https://github.com/ApolloAuto/apollo/blob/master/docs/quickstart/apollo_1_0_hardware_system_installation_guide.md
- https://github.com/mit-racecar
- https://github.com/topics/autonomous-vehicles
- https://autorally.github.io/build/
### Papers
- [Multi-View 3D Object Detection Network for Autonomous Driving](https://arxiv.org/pdf/1611.07759.pdf)
- [MobileNet](https://arxiv.org/pdf/1704.04861.pdf)
- [LIDAR-based 3D Object Perception](https://pdfs.semanticscholar.org/2c45/03c72ba7f53f3385859bd5e6311c58e73905.pdf)
- [End-to-end Driving via Conditional Imitation Learning](https://arxiv.org/pdf/1710.02410.pdf)
