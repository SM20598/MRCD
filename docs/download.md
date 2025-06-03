# Download MRCD
Below you find the download links for the MRCD dataset. The downloads feature our ROS2 bags for each sequence, the according ground truth trajectory, and the survey-grade prior map of the campus environment.



## Sequences

Below you find links to download all 8 sequences as complete versions of MRCD, including *Lightweight*, *Original*, *Survey-Grad Prior Map*, and *Continous Ground Truth*. For non-visual algorithm development, we recommend the **Lightweight bags**. For comprehensive algorithm development, which requires visual data, we recommend the **Original** bags. 

**Note** All of our provided ROS2 bags are in compressed format. Hence the first *GB* values denotes the download size, the second *GB* value in brackets denotes the uncompressed size.

| Version |
|-|
 [Download Size in GB (Uncompressed Size in GB)](https://sm20598.github.io/downloads)|

---

### Alley Fast (A I)
In Alley Fast, our robot moves at a higher velocity compared to all other sequences. It makes an immediate 90° turn before descending a steep path that leads to the open main campus area. Throughout the sequence, the robot passes tall buildings, diverse vegetation, and various dynamic obstacles, including pedestrians and cars.

![](gifs/alley_fast_left.gif)<br>
**Left Video Stream** (Original source has HD720 with 30FPS)

| Lighweight | Original | Continuous GT |
|-|-|-| 
| [1.1 GB (2.7 GB)](https://sm20598.github.io/downloads)| [42.6 GB (87.6 GB)](https://sm20598.github.io/downloads)| [0.0 GB](https://sm20598.github.io/downloads) |

---

### Alley Loop (A II)
Alley Loop extends the trajectory of Alley Fast and is the only bi-directional sequence in MRCD. In this sequence, the robot starts in the main campus area before ascending the same steep path featured in Alley Fast. At the northernmost point of the campus, it turns and follows the same path as in Alley Loop. The robot then enters a particularly narrow pathway, where it must navigate a series of sharp turns to reach the campus center. There, it turns around and follows the same trajectory in the opposite direction until it returns to its starting point. Alley Loop shares many characteristics with Alley Fast but presents additional challenges, including serpentine locomotion, greater height variations, and tighter spaces, alongside open environments.

![](gifs/alley_loop_left.gif)<br>
**Left Video Stream** (Original source has HD720 with 30FPS)

| Lighweight | Original | Continuous GT |
|-|-|-|
| [27.5 GB (43.2 GB)](https://sm20598.github.io/downloads)| [270.3 GB (494.6 GB)](https://sm20598.github.io/downloads)| [0.0 GB](https://sm20598.github.io/downloads) | 

---

### Grove Clockwise (G I)
In Grove Clockwise, the robot navigates through a predominantly green environment in the southern part of the campus. The trajectory loops around a central pond, which is surrounded by leafy trees, bushes, and buildings. Another notable characteristic is the consistently wet surface.

![](gifs/grove_clockwise_left.gif)<br>
**Left Video Stream** (Original source has HD720 with 30FPS)

| Lighweight | Original | Continuous GT |
|-|-|-|
| [2.4 GB (5.9 GB)](https://sm20598.github.io/downloads)| [74.6 GB (147.1 GB)](https://sm20598.github.io/downloads)| [0.0 GB](https://sm20598.github.io/downloads) | 

---

### Grove Counterclockwise (G II)
Grove Counterclockwise follows the same trajectory as Grove Clockwise but in opposite direction.

![](gifs/grove_counterclockwise_left.gif)<br>
**Left Video Stream** (Original source has HD720 with 30FPS)

| Lighweight | Original | Continuous GT |
|-|-|-|
| [2.6 GB (6.6 GB)](https://sm20598.github.io/downloads)| [78.7 GB (155.0 GB)](https://sm20598.github.io/downloads)| [0.0 GB](https://sm20598.github.io/downloads) | 

---

### Town Clockwise (T I)
Town Clockwise captures many of the campus environment's most challenging areas. The sequence begins in the main campus area, following the same initial path as Alley Fast and Alley Loop, but then takes a right turn. After traveling over a cobblestone surface, the robot encounters a variety of environmental conditions, including long narrow paths between tall buildings, uneven terrain, significant elevation changes, common obstacles such as bikes, cars, and trees, bright sunlight, and a mix of wide open and confined spaces.

![](gifs/town_clockwise_left.gif)<br>
**Left Video Stream** (Original source has HD720 with 30FPS)

| Lighweight | Original | Continuous GT |
|-|-|-|
| [8.2 GB (17.6 GB)](https://sm20598.github.io/downloads)| [154.7 GB (284.2 GB)](https://sm20598.github.io/downloads)| [0.0 GB](https://sm20598.github.io/downloads) | 

---

### Town Counterclockwise (T II)
Town Counterclockwise follows the same trajectory as Town Clockwise but in opposite direction.

![](gifs/town_counterclockwise_left.gif)<br>
**Left Video Stream** (Original source has HD720 with 30FPS)

| Lighweight | Original | Continuous GT |
|-|-|-|
| [8.0 GB (17.8 GB)](https://sm20598.github.io/downloads)| [162.0 GB (296.7 GB)](https://sm20598.github.io/downloads)| [0.0 GB](https://sm20598.github.io/downloads) | 

---

### Town Courtyard (T III)
Town Courtyard is a shorter sequence set within the town environment of the campus, featuring slalom-style driving between flowerboxes and bicycles. The challenging flowerbox navigation occurs once at the beginning and again at the end of the sequence, providing multiple opportunities for visual loop closure.

![](gifs/town_courtyard_left.gif)<br>
**Left Video Stream** (Original source has HD720 with 30FPS)

| Lighweight | Original | Continuous GT |
|-|-|-|
| [1.8 GB (4.4 GB)](https://sm20598.github.io/downloads)| [65.1 GB (123.4 GB)](https://sm20598.github.io/downloads)| [0.0 GB](https://sm20598.github.io/downloads) | 

---

### Town Trees (T IV)
Town Trees takes place at the North of the campus and provides further slalom-style locomotion in addition to traversal over cobblestone terrain. The trajectory of Town Trees stands out due to its scenarios of close-proximity maneuvers around leafy trees and self-intersecting trajectories in form of "donut" navigation.

![](gifs/town_trees_left.gif)<br>
**Left Video Stream** (Original source has HD720 with 30FPS)

| Lighweight | Original | Continuous GT |
|-|-|-|
| [2.9 GB (7.2 GB)](https://sm20598.github.io/downloads)| [89.9 GB (165.9 GB)](https://sm20598.github.io/downloads)| [0.0 GB](https://sm20598.github.io/downloads) |

---

## Docker Images
Below you find our provided Docker images for each SLAM algorithm. Please find the list and according repositories we used below. To download please klick on the links in Size column. For instructions on how to use, please refer to the [SLAM Tutorial](https://sm20598.github.io/slam-tutorial).


| Algorithm | Type We Used | Size |
|-|-|-|
| [FAST-LIO](https://github.com/hku-mars/FAST_LIO.git)| LiDAR-Inertial | [0.0 GB (4.41 GB)](https://sm20598.github.io/downloads)|
| [Cartographer](https://github.com/cartographer-project/cartographer) | LiDAR-Inertial | [0.0 GB (4.4 GB)](https://sm20598.github.io/downloads)|
| [NAV2 Slam Toolbox](https://github.com/SteveMacenski/slam_toolbox) | LiDAR-Inertial  | [0.0 GB (4.43 GB)](https://sm20598.github.io/downloads)|
| [Isaac ROS Visual SLAM](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_visual_slam) | Visual-Inertial   | [0.0 GB (36 GB)](https://sm20598.github.io/downloads)|
| [OpenVINS](https://github.com/rpng/open_vins/tree/master) | Visual-Inertial  | [0.0 (4.42 GB)](https://sm20598.github.io/downloads)|
| [RTAB-map](https://github.com/introlab/rtabmap_ros) | Visual-Inertial | [0.0 GB (0.0 GB)](https://sm20598.github.io/downloads)|
| [ORB-SLAM3-ROS2](https://github.com/jnskkmhr/orbslam3) | Visual | [0.0 GB (9.58 GB)](https://sm20598.github.io/downloads)|

---

## Survey-Grade Prior Map
Please find our survey-grade prior maps in resolution of 1cm and 5cm below.

| 1cm resolution | 5cm resolution |
|-|-|
| [11.6 GB](https://sm20598.github.io/downloads)| [1.3 GB](https://sm20598.github.io/downloads)|