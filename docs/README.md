# [MRCD: Mobile Robot Campus Dataset](https://sm20598.github.io/MRCD)
The Mobile Robot Campus Dataset (MRCD) presents a novel outdoor SLAM challenge dedicated to testing, evaluating, and developing SOTA algorithms.
Our contribution includes diverse challenging, high-frequency robot sequences collected with a wheeled delivery robot, an commnunity-driven competition for modern SLAM algorithms and a qualitive benchmark of exisiting ROS2-based SLAM algorithms available online. With MRCD, we aim to contribute to the ongoing development of SLAM algorithms highlighting existing limitations and challenges, in particular related to ROS2 implementations, and hope to address open problems, issues, and challenges in a collaborative fashion.   

![](photos_resized/Roboter_anonym.png#center)

## Dataset Content
MRCD provides several ROS2 bag files that include various sensor modalities:

* 📷 HD720 30 FPS stereo frontal camera streams
* ☁️ High resolution visual frontal pointcloud
* 📷 HD720 30 FPS mono depth + colored ground-facing camera streams 
* 📏 3D spinning LiDAR
* ⬆️ High-frequent IMUs (raw accelerometer, gyroscope and magnetometer data) 
* 🛞 Odometry of our wheeled robot
* 📍 Highly accurate GPS-measurements
* 👣 Embedded discrete (+ external continuous) ground truth messages
* 🌍 High resolution large scale survey grade prior map of the campus environment
* [Docker Images](./download.md#docker-images) for Humble SOTA SLAM algorithms.

## Open-Community Benchmark Challenge
In addition to our dataset, we present the MRCD-SLAM challenge, where reachers will have the opportunity to compete against eachother.

## Notes:
We are open to contributions to our dataset. Please feel free to raise an [issue](https://github.com/SM20598/MRCD/issues) or open a [discussion](https://github.com/SM20598/MRCD/discussions) on our [Github](https://github.com/SM20598/MRCD) 🙃
<!-- ## Publication:
For more information, please find our publication below. If you use MRCD or reference our work, we kindly ask that you cite it as follows:

```bibtex
@article{mrcd2025,
  title={MRCD: Mobile Robot Campus Dataset for Evaluating SLAM Algorithms on Wheeled Robots},
  author={Doe, John},
  journal={arXiv},
  year={2026}
}
``` -->
<!-- 
[Arxiv](https://arxiv.org/)
[Supplementary Material](https://arxiv.org/) -->

<!-- ---

This work was funded by the [Federal Ministry for Digital and Transport Affairs](https://www.bmv.de/DE/Home/home.html)

<body>
    <div class="imgContainerLeft">
      <a href="https://www3.tuhh.de/itl/en/">
        <img style="float: left;" src="img/ITL_logo.png" width="250" >
      </a>
    </div>
    <div class="imgContainer">
      <a href="https://www3.tuhh.de/itl/en/">
        <img style="float: left;" src="img/TUHH_logo.png" width="140">
      </a>
    </div>
    <div class="imgContainer">
      <a href="https://www3.tuhh.de/itl/en/">
        <img style="float: left;" src="img/BMV_Logo.png" width="200">
      </a>
    </div>
</body> -->