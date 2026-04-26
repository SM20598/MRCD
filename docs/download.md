# Download MRCD
Below you find the download links for the MRCD dataset. The downloads feature our ROS2 bags for each sequence, the according ground truth trajectory, and the survey-grade prior map of the campus environment. If any of the links is broken, a list of manuall downloads can be found [link]
[here](https://tore.tuhh.de/entities/product/db4dad9e-5c2d-451f-bd12-90dd0226cfd5).

**Download links and videos are added after review**

## Sequences

Below you find links to download all 8 sequences as complete versions of MRCD, including *Lightweight*, *Original*, *Survey-Grad Prior Map*, and *Continous Ground Truth*. For non-visual algorithm development, we recommend the **Lightweight bags**. For comprehensive algorithm development, which requires visual data, we recommend the **Original** bags. 

**Note** All of our provided ROS2 bags are in compressed format. Hence the first *GB* values denotes the download size, the second *GB* value in brackets denotes the uncompressed size. Below an example

| Version |
|-|
 [Download Size in GB (Uncompressed Size in GB)](https://sm20598.github.io/downloads)|

---

### Alley Fast (A I)
In Alley Fast, our robot moves at a higher velocity compared to all other sequences. It makes an immediate 90° turn before descending a steep path that leads to the open main campus area. Throughout the sequence, the robot passes tall buildings, diverse vegetation, and various dynamic obstacles, including pedestrians and cars.

<!-- ![](gifs/alley_fast_left.gif)<br> -->
**Left Video Stream** (Original source has HD720 with 30FPS)

| Lighweight | Original | Continuous Spline GT | 10Hz Sampled GT |
|-|-|-|-|
<!-- | [1.06 GB (2.7 GB)](https://tore.tuhh.de/bitstreams/c3cfcdb1-aae3-4615-906b-79fc607ddf8a/download)| [39.64 GB (87.6 GB)](https://tore.tuhh.de/bitstreams/bf3f67ce-95ea-40e5-b4be-a95b67755f44/download)| [2.82 MB](https://tore.tuhh.de/bitstreams/435b9e1c-0af9-4080-aa47-57911b87fe5a/download) | [158.05 KB](https://tore.tuhh.de/bitstreams/69aa3141-df18-4a43-8298-4e4bc1f6f1e8/download) | -->

---

### Alley Loop (A II)
Alley Loop extends the trajectory of Alley Fast and is the only bi-directional sequence in MRCD. In this sequence, the robot starts in the main campus area before ascending the same steep path featured in Alley Fast. At the northernmost point of the campus, it turns and follows the same path as in Alley Loop. The robot then enters a particularly narrow pathway, where it must navigate a series of sharp turns to reach the campus center. There, it turns around and follows the same trajectory in the opposite direction until it returns to its starting point. Alley Loop shares many characteristics with Alley Fast but presents additional challenges, including serpentine locomotion, greater height variations, and tighter spaces, alongside open environments.

<!-- ![](gifs/alley_loop_left.gif)<br> -->
**Left Video Stream** (Original source has HD720 with 30FPS)

| Lighweight | Original | Continuous Spline GT | 10Hz Sampled GT |
|-|-|-|-|
<!-- | [25.63 GB (43.2 GB)](https://tore.tuhh.de/bitstreams/7a5aed8b-7213-4a3e-9dec-e05e9cab1cd7/download)| [251.73 GB (494.6 GB)](https://tore.tuhh.de/bitstreams/001b5b6a-d4d4-44af-919a-258a15b74255/download)| [15.1 MB](https://tore.tuhh.de/bitstreams/3e25bcc3-b6f9-4496-acc4-223a57d16516/download) | [842.59 KB](https://tore.tuhh.de/bitstreams/6800ee87-803e-461e-8501-f544928c4588/download) | -->

---

### Grove Clockwise (G I)
In Grove Clockwise, the robot navigates through a predominantly green environment in the southern part of the campus. The trajectory loops around a central pond, which is surrounded by leafy trees, bushes, and buildings. Another notable characteristic is the consistently wet surface.

<!-- ![](gifs/grove_clockwise_left.gif)<br> -->
**Left Video Stream** (Original source has HD720 with 30FPS)

| Lighweight | Original | Continuous Spline GT | 10Hz Sampled GT |
|-|-|-|-|
<!-- | [2.25 GB (5.9 GB)](https://tore.tuhh.de/bitstreams/529e0620-3c16-4df2-baad-b87d0ded14e2/download)| [69.49 GB (147.1 GB)](https://tore.tuhh.de/bitstreams/bf9c5ae8-2647-4b65-8081-999805f8586f/download)| [4.8 MB](https://tore.tuhh.de/bitstreams/7e00ca69-bfc9-4ec8-b084-bf713a94dff4/download) | [265.05 KB](https://tore.tuhh.de/bitstreams/b734014c-2b21-4b8b-acb1-591167a648f5/download) |  -->

---

### Grove Counterclockwise (G II)
Grove Counterclockwise follows the same trajectory as Grove Clockwise but in opposite direction.

<!-- ![](gifs/grove_counterclockwise_left.gif)<br> -->
**Left Video Stream** (Original source has HD720 with 30FPS)

| Lighweight | Original | Continuous Spline GT | 10Hz Sampled GT |
|-|-|-|-|
<!-- | [2.41 GB (6.6 GB)](https://tore.tuhh.de/bitstreams/de6ec73d-b4d9-4482-88ce-243e17ec66f5/downloads)| [73.28 GB (155.0 GB)](https://tore.tuhh.de/bitstreams/7973df04-3fa9-4a9f-82dd-0e722b914220/download)| [5.09 MB](https://tore.tuhh.de/bitstreams/a1c68c60-f323-42ec-b421-c36020b2fc74/download) |  [280.34 KB](https://tore.tuhh.de/bitstreams/19ba46a3-0dd9-4d5e-8ab3-f0c8bd156e17/download) |  -->

---

### Town Clockwise (T I)
Town Clockwise captures many of the campus environment's most challenging areas. The sequence begins in the main campus area, following the same initial path as Alley Fast and Alley Loop, but then takes a right turn. After traveling over a cobblestone surface, the robot encounters a variety of environmental conditions, including long narrow paths between tall buildings, uneven terrain, significant elevation changes, common obstacles such as bikes, cars, and trees, bright sunlight, and a mix of wide open and confined spaces.

<!-- ![](gifs/town_clockwise_left.gif)<br> -->
**Left Video Stream** (Original source has HD720 with 30FPS)

| Lighweight | Original | Continuous Spline GT | 10Hz Sampled GT |
|-|-|-|-|
<!-- | [7.65 GB (17.6 GB)](https://tore.tuhh.de/bitstreams/852237ba-f46a-4897-bc64-9f96eee757cb/download)| [144 GB (284.2 GB)](https://tore.tuhh.de/bitstreams/19f3f27f-87e5-4275-b700-16c9f5c1b900/download)| [8.99 MB](https://tore.tuhh.de/bitstreams/8534e6b6-4232-4231-8aae-63f8813f809d/download) | [505.99 KB](https://tore.tuhh.de/bitstreams/83d6ad63-64df-4e94-ac40-932e2ce5e2f0/download) |  -->

---

### Town Counterclockwise (T II)
Town Counterclockwise follows the same trajectory as Town Clockwise but in opposite direction.

<!-- ![](gifs/town_counterclockwise_left.gif)<br> -->
**Left Video Stream** (Original source has HD720 with 30FPS)

| Lighweight | Original | Continuous Spline GT | 10Hz Sampled GT |
|-|-|-|-|
<!-- | [7.47 GB (17.8 GB)](https://tore.tuhh.de/bitstreams/a595dcdb-618a-4d47-ba51-28c5612ecfb8/download)| [150.8 GB (296.7 GB)](https://tore.tuhh.de/bitstreams/062eda5f-f524-44f8-a356-3d0cdfcba899/download)| [9.14 MB](https://tore.tuhh.de/bitstreams/da231545-faa2-4faa-87b0-6fd1cba6f84b/download) | [510.66 KB](https://tore.tuhh.de/bitstreams/829c71b5-35f8-4f8a-8491-d6f1275597dd/download) |  -->

---

### Town Courtyard (T III)
Town Courtyard is a shorter sequence set within the town environment of the campus, featuring slalom-style driving between flowerboxes and bicycles. The challenging flowerbox navigation occurs once at the beginning and again at the end of the sequence, providing multiple opportunities for visual loop closure.

<!-- ![](gifs/town_courtyard_left.gif)<br> -->
**Left Video Stream** (Original source has HD720 with 30FPS)

| Lighweight | Original | Continuous Spline GT | 10Hz Sampled GT |
|-|-|-|-|
<!-- | [1.7 GB (4.4 GB)](https://tore.tuhh.de/bitstreams/95819a75-850b-45aa-956c-177088584fd2/download)| [60.62 GB (123.4 GB)](https://tore.tuhh.de/bitstreams/f4efd021-13f4-4a4c-848d-6088e55eeb11/download)| [3.96 MB](https://tore.tuhh.de/bitstreams/92c7a522-53aa-430e-bf2f-dc5e8d44299c/download) | [219.27 KB](https://tore.tuhh.de/bitstreams/a193257b-d910-47bc-9fe3-92cd6424fdfb/download) |  -->

---

### Town Trees (T IV)
Town Trees takes place at the North of the campus and provides further slalom-style locomotion in addition to traversal over cobblestone terrain. The trajectory of Town Trees stands out due to its scenarios of close-proximity maneuvers around leafy trees and self-intersecting trajectories in form of "donut" navigation.

<!-- ![](gifs/town_trees_left.gif)<br> -->
**Left Video Stream** (Original source has HD720 with 30FPS)

| Lighweight | Original | Continuous Spline GT | 10Hz Sampled GT |
|-|-|-|-|
<!-- | [2.74 GB (7.2 GB)](https://tore.tuhh.de/bitstreams/94cc72f3-e252-4d50-ba60-790654f38954/download)| [83.72 GB (165.9 GB)](https://tore.tuhh.de/bitstreams/b31ceede-d640-4919-8d5e-1f2f112957d1/download)| [5.36 MB](https://tore.tuhh.de/bitstreams/0772dfc7-0d3f-4f3d-a389-f7d22cf82e06/download) | [301.02 KB](https://tore.tuhh.de/bitstreams/46f23d96-6138-46d2-a47c-bb1cb870bb7a/download) |  -->

---

## Docker Images
Below you find our provided Docker images for each SLAM algorithm and the evaluation container. Please find the list and according repositories we used below. To download please klick on the links in Size column. For instructions on how to use, please refer to the [SLAM Tutorial](https://sm20598.github.io/slam-tutorial) page. We included our quick-and-dirty evaluation script in the container for reference, but recommend writing your own.

Note that the RTAB-map container is based on Isaac ROS Visual SLAM container. If you want to run both you will only need the first.


| Algorithm | Type We Used | Size |
|-|-|-|
| [FAST-LIO](https://github.com/hku-mars/FAST_LIO.git)| LiDAR-Inertial | [5.29 GB (5.29 GB)](https://tore.tuhh.de/bitstreams/8c6b75a5-dd78-4848-9b88-960ac55ee103/download)|
| [Cartographer](https://github.com/cartographer-project/cartographer) | LiDAR-Inertial | [5.35 GB (5.35 GB)](https://tore.tuhh.de/bitstreams/0950a2c4-21db-46cc-a50b-ab540cc77ef4/download)|
| [Isaac ROS Visual SLAM](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_visual_slam) | Visual-Inertial   | [36.24 GB (36.24 GB)](https://tore.tuhh.de/bitstreams/71463d37-b7ce-44f5-9ae7-af3e48528b25/download)|
| [NAV2 Slam Toolbox](https://github.com/SteveMacenski/slam_toolbox) | LiDAR-Inertial  | [4.3 GB (4.3 GB)](https://tore.tuhh.de/bitstreams/b18b747a-29cd-42cb-ba3e-4de002ba448e/download)|
| [OpenVINS](https://github.com/rpng/open_vins/tree/master) | Visual-Inertial  | [7.53 GB (7.53 GB)](https://tore.tuhh.de/bitstreams/a12de53b-ca49-4adc-b059-9447b4f726bd/download)|
| [RTAB-map](https://github.com/introlab/rtabmap_ros) | Visual-Inertial | [35.3 GB (35.3 GB)](https://tore.tuhh.de/bitstreams/b18b747a-29cd-42cb-ba3e-4de002ba448e/download)|
| [ORB-SLAM3-ROS2](https://github.com/jnskkmhr/orbslam3) | Visual | [7 GB (7 GB)](https://tore.tuhh.de/bitstreams/cd861bd8-e88a-4def-a487-cba15daece72/download)|
| [Evaluation](https://mcdviral.github.io/Groundtruth.html) | Evaluation | [4.81 GB (4.81 GB)](https://tore.tuhh.de/bitstreams/a0012a26-9c9e-4b20-8973-56d55e5ff2a8/download)|

---

## Survey-Grade Prior Map
Please find our survey-grade prior maps in resolution of 1cm and 5cm below.

| 1cm resolution | 5cm resolution |
|-|-|
<!-- | [10.81 GB](https://tore.tuhh.de/bitstreams/7d218085-1b8d-404e-8aae-274eb8f227c3/download)| [1.23 GB](https://tore.tuhh.de/bitstreams/c2881037-ae9d-42d9-9d4d-80929696fe3a/download)| -->