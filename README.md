# rpi-bullseye-ROS2

Build ROS2-Humble for Raspbian-bullseye

Scripts for build ROS2 to running on Raspbian (64bit).

![](./images_for_readme//rviz_rpi.jpg)

<br>

## Support

### Latest : ros2-0.2.0

[ros2-0.2.0](https://github.com/Ar-Ray-code/rpi-bullseye-ros2/releases/tag/ros2-0.2.0)

| Version | aarch64 |
| --- | --- |
| humble | ✔ |
| galactic | |

<br>

<details><summary>ros2-0.1.0</summary>

[ros2-0.1.0](https://github.com/Ar-Ray-code/rpi-bullseye-ros2/releases/tag/ros2-0.1.0)


### ❌ Excluded packages ❌

- RViz
- rosbag
- rqt

<br>

| Version | aarch64 | arm7l |
| --- | --- | --- |
| humble | ✔ | ✔ |
| galactic | | ✔ |

</details>

<br>

<br>

## Install

- OS   : RaspberryPi OS bullseye aarch64
- ROS2 : ROS2 Humble

```bash
# (humble, aarch64)
wget https://raw.githubusercontent.com/Ar-Ray-code/rpi-bullseye-ros2/main/install.bash
bash install.bash humble aarch64 0.2.0 /opt/ros
```

Load ROS2

```bash
source /opt/ros/humble/setup.bash
```

<br>

## Build

[README](./build/README.md)

<br>

## About author

- author : [Ar-Ray](https://github.com/Ar-Ray-code)
- [Twitter](https://twitter.com/Ray255Ar)
