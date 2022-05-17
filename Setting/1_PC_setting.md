#### 1. "Ubuntu20.04 LTS desktop"을 USB에 굽는다.

#### 2. 아래 사이트를 참조하여 PC가 듀얼 부팅 되도록 만든다.
      https://dreamdeveloper403.tistory.com/27
      
#### 3. cmd 창에 아래 코드를 친다.
`sudo apt update`  

`sudo apt upgrade`

// Install ROS2 Foxy

`wget https://raw.githubusercontent.com/ROBOTIS-GIT/robotis_tools/master/install_ros2_foxy.sh`

 `sudo chmod 755 ./install_ros2_foxy.sh`
 
 `bash ./install_ros2_foxy.sh`
 
 // Install Gazebo11 
 
 `sudo apt-get install ros-foxy-gazebo-*`
 
 //Install Cartographer
 
 `sudo apt install ros-foxy-cartographer`
 
 `sudo apt install ros-foxy-cartographer-ros`
 
 //Install Navigation2
 
 `sudo apt install ros-foxy-navigation2`
 
 `sudo apt install ros-foxy-nav2-bringup`
 
 
 // Install TurtleBot3 via Debian Packages.
 
 `source ~/.bashrc`
 
 `sudo apt install ros-foxy-dynamixel-sdk`
 
 `sudo apt install ros-foxy-turtlebot3-msgs`
 
 `sudo apt install ros-foxy-turtlebot3`
 
 // Set the ROS environment for PC
 
 `echo 'export ROS_DOMAIN_ID=30 #TURTLEBOT3' >> ~/.bashrc`
 
 `source ~/.bashrc `
 
----
#### .bashrc 확인 및 저장
`gedit ~/.bashrc`
`source ~/.bashrc`

----
참고자료: https://emanual.robotis.com/docs/en/platform/turtlebot3/quick-start/#pc-setup
