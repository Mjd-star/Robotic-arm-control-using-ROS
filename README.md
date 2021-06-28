# Robotic-arm-control-using-ROS
# install virtualBox
# configure the virtualBox
# installing ubunto 18.0 on virtualBox
# install Ros melodic
# install arduino robot arm packages
1- these instructions in terminal
2- sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
3- sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654
4- sudo apt-get update
5- sudo apt-get install ros-melodic-desktop-full
6- sudo apt-get install ros-melodic-desktop-full
7- apt-cache search ros-melodic
8- echo "source /opt/ros/melodic/setup.bash" >> ~/.bashrc
9- source ~/.bashrc
10- sudo apt install python-rosdep python-rosinstall python-rosinstall-generator python-wstool build-essential
11- sudo apt install python-rosdep
12- sudo rosdep init
13- rosdep update
14- sudo apt-get install ros-noetic-catkin
15- mkdir -p ~/catkin_ws/src
16- cd ~/catkin_ws/
17- catkin_make
18- cd ~/catkin_ws/src
19- git clone https://github.com/smart-methods/arduino_robot_arm.git
20- cd ~/catkin_ws
21- rosdep install --from-paths src --ignore-src -r -y
22- sudo apt-get install ros-melodic-moveit
23- sudo apt-get install ros-melodic-joint-state-publisher ros-melodic-joint-state-publisher-gui
24- sudo apt-get install ros-melodic-gazebo-ros-control joint-state-publisher
25- sudo nano ~/.bashrc
26- source /home/mjd/catkin_ws/devel/setup.bash
27- source ~/.bashrc
28- roslaunch robot_arm_pkg check_motors.launch
# simulation 
Run the following instruction to use gazebo Rivz
roslaunch robot_arm_pkg check_motors.launch
![03d2e118-1eb8-4ee0-b1c7-beaccc35c62a](https://user-images.githubusercontent.com/85651071/123658386-5aeb3980-d83a-11eb-9c4c-7a15a6594c5c.jpg)
![43363915-c9ce-42d9-97c6-820fa658673b](https://user-images.githubusercontent.com/85651071/123658488-72c2bd80-d83a-11eb-9113-cb09e7e7f04d.jpg)
![66fc3fa5-efbb-47d5-acf4-408fd977109a](https://user-images.githubusercontent.com/85651071/123658580-89691480-d83a-11eb-9710-9c03c7b76281.jpg)







