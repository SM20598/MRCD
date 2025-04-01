# Download MRCD
Below you find the download links for the MRCD dataset. The downloads feature our ROS2 bags for each sequence, the according ground truth trajectory, and the survey-grade prior map of the campus environment.



## Dataset

Below you find links to download all 8 sequences as complete versions of MRCD, including *Lightweight*, *Original*, *Survey-Grad Prior Map*, and *Continous Ground Truth*. For non-visual algorithm development, we recommend the **Lightweight bags**. For comprehensive algorithm development, which requires visual data, we recommend the **Original** bags. 

---
**Note** All of our provided ROS2 bags are in compressed format. Hence the first *GB* values denotes the download size, the second *GB* value in brackets denotes the uncompressed size.

*Notation:*

| Version |
|-|
 [Download Size in GB (Uncompressed Size in GB)](https://sm20598.github.io/downloads)|


---

### Complete Version
Download all 8 sequences at once.

| Lighweight | Original | Continuous GT |
|-|-|-|
| [0.0 GB (0.0 GB)](https://sm20598.github.io/downloads)| [0.0 GB (0.0 GB)](https://sm20598.github.io/downloads)| [0.0 GB](https://sm20598.github.io/downloads) |

### Alley Fast (A I)
In this sequences, our robot drives with higher velocity from North to South of the campus environment. The environment features tall buildings, height differences, and changing vegetation.

| Lighweight | Original | Continuous GT |
|-|-|-| 
| [1.1 GB (2.7 GB)](https://sm20598.github.io/downloads)| [42.6 GB (87.6 GB)](https://sm20598.github.io/downloads)| [0.0 GB](https://sm20598.github.io/downloads) |

### Alley Loop (A II)
This sequence has similar characteristics to the Alley Fast sequence. However, the sequences includes loop closure and the robot drives with lower velocity.

| Lighweight | Original | Continuous GT |
|-|-|-|
| [27.5 GB (43.2 GB)](https://sm20598.github.io/downloads)| [270.3 GB (147.1 GB)](https://sm20598.github.io/downloads)| [0.0 GB](https://sm20598.github.io/downloads) | 

### Groove Loop Clockwise (G I)
The environment of this sequence is characterized by a grove with leafy trees, wet soil, and a small pond. The robot drives in a clockwise loop around the pond.

| Lighweight | Original | Continuous GT |
|-|-|-|
| [2.4 GB (5.9 GB)](https://sm20598.github.io/downloads)| [74.6 GB (147.1 GB)](https://sm20598.github.io/downloads)| [0.0 GB](https://sm20598.github.io/downloads) | 

### Grove Loop Counter Clockwise (G II)
Same features as the Grove Loop Clockwise sequence, but the robot drives in a counter clockwise loop around the pond.

| Lighweight | Original | Continuous GT |
|-|-|-|
| [2.6 GB (6.6 GB)](https://sm20598.github.io/downloads)| [78.7 GB (155.0 GB)](https://sm20598.github.io/downloads)| [0.0 GB](https://sm20598.github.io/downloads) | 

### Town Loop Clockwise (T I)
Town Loop Clockwise features varying environment characteristics, such as long narrow paths between tall buildings, uneven terrain, strong height differences, common obstacles (bikes, cars, trees), bright sunlight, and wide open and closed spaces.

| Lighweight | Original | Continuous GT |
|-|-|-|
| [8.2 GB (17.6 GB)](https://sm20598.github.io/downloads)| [154.7 GB (284.2 GB)](https://sm20598.github.io/downloads)| [0.0 GB](https://sm20598.github.io/downloads) | 

### Town Loop Counter Clockwise (T II)
Same features as the Town Loop Clockwise sequence, but the robot drives in a counter clockwise loop.

| Lighweight | Original | Continuous GT |
|-|-|-|
| [8.0 GB (17.8 GB)](https://sm20598.github.io/downloads)| [162.0 GB (296.7 GB)](https://sm20598.github.io/downloads)| [0.0 GB](https://sm20598.github.io/downloads) | 

### Town Courtyard (T III)
A shorter sequence within the town environment of the campus, featuring slalom driving between flowboxes.

| Lighweight | Original | Continuous GT |
|-|-|-|
| [1.8 GB (4.4 GB)](https://sm20598.github.io/downloads)| [65.1 GB (123.4 GB)](https://sm20598.github.io/downloads)| [0.0 GB](https://sm20598.github.io/downloads) | 

### Town Tree (T IV)
Another short sequence within the town environment of the campus, featuring the uneven terrain and trees of the campus environment.

| Lighweight | Original | Continuous GT |
|-|-|-|
| [2.9 GB (7.2 GB)](https://sm20598.github.io/downloads)| [89.9 GB (165.9 GB)](https://sm20598.github.io/downloads)| [0.0 GB](https://sm20598.github.io/downloads) |

## Docker Images
Below you find our provided Docker images for each SLAM algorithm. Please find the list and according Repositories we used below. To download please klick on the links in Size column. For instructions on how to use, please refer to the [SLAM Tutorial](https://sm20598.github.io/slam-tutorial).


| Algorithm | Type We Used | Size |
|-|-|-|
| [FAST-LIO](https://github.com/hku-mars/FAST_LIO.git)| LiDAR-Inertial | [0.0 GB (4.41 GB)](https://sm20598.github.io/downloads)|
| [Cartographer](https://github.com/cartographer-project/cartographer) | LiDAR-Inertial | [0.0 GB (4.4 GB)](https://sm20598.github.io/downloads)|
| [NAV2 Slam Toolbox](https://github.com/SteveMacenski/slam_toolbox) | LiDAR-Inertial  | [0.0 GB (4.43 GB)](https://sm20598.github.io/downloads)|
| [Isaac ROS Visual SLAM](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_visual_slam) | Visual-Inertial   | [0.0 GB (36 GB)](https://sm20598.github.io/downloads)|
| [OpenVINS](https://github.com/rpng/open_vins/tree/master) | Visual-Inertial  | [0.0 (4.42 GB)](https://sm20598.github.io/downloads)|
| [RTAB-map](https://github.com/introlab/rtabmap_ros) | Visual-Inertial | [0.0 GB (0.0 GB)](https://sm20598.github.io/downloads)|
| [ORB-SLAM3-ROS2](https://github.com/jnskkmhr/orbslam3) | Visual | [0.0 GB (9.58 GB)](https://sm20598.github.io/downloads)|
