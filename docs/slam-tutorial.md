# SLAM Tutorial
MRCD was tested using a handful of state-of-the-art SLAM algorithms, which demonstrate the capabilities of the recorded dataset.

## Algorithms
We provide ROS2-Humble Docker images for each algorithm, which can be downloader here [LINK?]. Please find the list and according Repositories we used below.

### LiDAR-Inertial SLAM
* Fast LiDAR-Inertial Odometry [FAST-LIO](https://github.com/hku-mars/FAST_LIO.git)
* Google Cartographer [Cartographer](https://github.com/cartographer-project/cartographer)
* Nav2 SLAM Toolbox [Slam Toolbox](https://github.com/SteveMacenski/slam_toolbox)

### Visual-Inertial SLAM
* NVIDIA ISSAC ROS [Isaac ROS Visual SLAM](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_visual_slam)
* Open Visual-Inertial Navigation System [OpenVINS](https://github.com/rpng/open_vins/tree/master)
* Real-Time Appearance-Based Mapping [RTAB-map](https://github.com/introlab/rtabmap_ros)

### Visual SLAM
* ORB SLAM 3 [ORB-SLAM3-ROS2](https://github.com/jnskkmhr/orbslam3)

## How To Use?
For evaluation using the aforementioned SLAM algorithms, we recommend using our provided [Docker Images](link) and follow the install instructions in the Install guide.. However, you may want to check if the repositories in the list above have been updated. For example, the repository that we used for ORB SLAM3 features instable stereo-inertial SLAM at this time.
