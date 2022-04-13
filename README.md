# hector_quadrotor ported to ROS Noetic & Gazebo 11

<img src="imgs/dron_photo.png" height="250"/> <img src="imgs/dron_photo_rviz.png" height="250"/>

***.:: First version, please tell me the issues or help me to fix it ::.***

I took part of this from __The Construct's__ [repo](https://bitbucket.org/theconstructcore/hector_quadrotor_sim/src/master/) and YouTube [chanel](https://www.youtube.com/channel/UCt6Lag-vv25fTX3e11mVY1Q).

## Requirements

I. You need the following packages before install `hector_quadrotor_noetic`.

* unique_identifier:
    ```sh
    git clone https://github.com/ros-geographic-info/unique_identifier.git
    ```
* geographic_info:
    ```sh
    git clone https://github.com/ros-geographic-info/geographic_info.git
    ```

II. Build.
```sh
cd ~/catkin_ws && catkin_make
```

III. Clone `hector_quadrotor_noetic`.
```sh
git clone https://github.com/RAFALAMAO/hector_quadrotor_noetic.git
```

IV. Repeat step II.

## Usage

Run a simulation by executing the launch file in `hector_quadrotor_gazebo` and `hector_quadrotor_demo` packages (only these work at the momment, but you can try the other ones):

* `roslaunch hector_quadrotor_gazebo quadrotor_empty_world.launch`
* `roslaunch hector_quadrotor_demo outdoor_flight_gazebo.launch`
* `roslaunch hector_quadrotor_demo outdoor_flight_gazebo_no_rviz.launch`
* `roslaunch hector_quadrotor_demo two_drones_empty.launch`

You can control it with teleop_twist_keyboard.
* `git clone https://github.com/ros-teleop/teleop_twist_keyboard`

## Test

Here is a [video](https://www.youtube.com/watch?v=-2IWfZjqoNc) testing it:

<<<<<<< HEAD
😊😊😊 ayhan
=======
[![IMAGE ALT TEXT HERE](https://github.com/RAFALAMAO/hector_quadrotor_noetic/blob/main/imgs/gif.GIF)](https://www.youtube.com/watch?v=-2IWfZjqoNc)
>>>>>>> 8d077915de22a36059f2beb96214bc13ee442b09
