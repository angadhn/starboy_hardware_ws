# starboy_hardware_ws
1. Clone the repo
2. `cd starboy_hardware_ws`
3. `caktin_make`
4. If you get an error message saying msg_confisg missing then
`sudo apt-get install ros-<distro>-industrial-msgs`

Hooking up to the robot
-----------------------
1. `source devel/setup.bash`
2. `roslaunch ur_modern_driver ur5_bringup_joint_limited.launch robot_ip:=192.168.0.50`
