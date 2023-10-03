# AprilTag ROS 2
### AprilTag Detection and Tracking with ROS 2


## Build:
1. Make a directory `ros_ws` to act as your ROS 2 workspace.
    ```bash
    $ mkdir -p ~/ros_ws/src/
    ```
2. Clone this repository:
    ```bash
    $ git clone https://github.com/Olin-RoboSys/AprilTag-ROS-2.git
    ```
3. Build the packages.
    ```bash
    $ cd ~/ROS2_WS
    $ colcon build
    ```
4. Source the `setup.bash` file of your `ROS2_WS`.
    ```bash
    $ echo "source ~/ros_ws/install/setup.bash" >> ~/.bashrc
    $ source ~/.bashrc
    ```

## Execute:
```bash
$ ros2 launch apriltag_ros apriltag_ros.launch.py
```

## Acknowledgement:
This repository was heavily adapted from the [AprilTag Detection and Tracking from Tinker-Twins](https://github.com/Tinker-Twins/AprilTag).
