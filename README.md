# SMS_MS
```
ubuntu2005@ubuntu:~$ mkdir projectw3_ws
ubuntu2005@ubuntu:~$ cd projectw3_ws/
ubuntu2005@ubuntu:~/projectw3_ws$ mkdir src
ubuntu2005@ubuntu:~/projectw3_ws$ cd src
ubuntu2005@ubuntu:~/projectw3_ws/src$ catkin_create_pkg projectw3
Created file projectw3/package.xml
Created file projectw3/CMakeLists.txt
Successfully created files in /home/ubuntu2005/projectw3_ws/src/projectw3. Please adjust the values in package.xml.
ubuntu2005@ubuntu:~/projectw3_ws/src$ catkin_create_pkg projectw3 roscpp
usage: catkin_create_pkg [-h] [--meta] [-s [SYS_DEPS [SYS_DEPS ...]]]
                         [-b [BOOST_COMPS [BOOST_COMPS ...]]] [-V PKG_VERSION]
                         [-D DESCRIPTION] [-l LICENSE] [-a AUTHOR]
                         [-m MAINTAINER] [--rosdistro ROSDISTRO]
                         name [dependencies [dependencies ...]]
catkin_create_pkg: error: File exists: /home/ubuntu2005/projectw3_ws/src/projectw3/package.xml
ubuntu2005@ubuntu:~/projectw3_ws/srcuuubuntu2ubuubuuubuubunubuubuuubuntubuububuububuntubuubuntuubuntu2005@ubuntu:~/projectw3_ws/src$
```































ubuntu2005@ubuntu:~$ sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
[sudo] password for ubuntu2005: 
ubuntu2005@ubuntu:~$ sudo apt install curl # if you haven't already installed curl
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following packages were automatically installed and are no longer required:
  linux-headers-5.15.0-46-generic linux-hwe-5.15-headers-5.15.0-46
  linux-image-5.15.0-46-generic linux-modules-5.15.0-46-generic
  linux-modules-extra-5.15.0-46-generic
Use 'sudo apt autoremove' to remove them.
The following additional packages will be installed:
  libcurl4 libcurl4-openssl-dev
Suggested packages:
  libcurl4-doc libidn11-dev librtmp-dev libssh2-1-dev
The following packages will be upgraded:
  curl libcurl4 libcurl4-openssl-dev
3 upgraded, 0 newly installed, 0 to remove and 130 not upgraded.
Need to get 719 kB of archives.
After this operation, 5,120 B of additional disk space will be used.
Do you want to continue? [Y/n] y
Abort.
ubuntu2005@ubuntu:~$ 





ubuntu2005@ubuntu:~$ sudo apt update
Hit:1 http://security.ubuntu.com/ubuntu focal-security InRelease
Hit:2 http://packages.ros.org/ros/ubuntu focal InRelease 
Hit:3 http://us.archive.ubuntu.com/ubuntu focal InRelease
Hit:4 http://us.archive.ubuntu.com/ubuntu focal-updates InRelease
Hit:5 http://us.archive.ubuntu.com/ubuntu focal-backports InRelease
Reading package lists... Done
Building dependency tree       
Reading state information... Done
133 packages can be upgraded. Run 'apt list --upgradable' to see them.
ubuntu2005@ubuntu:~$ 














ubuntu2005@ubuntu:~$ sudo apt install ros-noetic-desktop-full
Reading package lists... Done
Building dependency tree       
Reading state information... Done
ros-noetic-desktop-full is already the newest version (1.5.0-1focal.20230225.005309).
The following packages were automatically installed and are no longer required:
  linux-headers-5.15.0-46-generic linux-hwe-5.15-headers-5.15.0-46
  linux-image-5.15.0-46-generic linux-modules-5.15.0-46-generic
  linux-modules-extra-5.15.0-46-generic
Use 'sudo apt autoremove' to remove them.
0 upgraded, 0 newly installed, 0 to remove and 133 not upgraded.
ubuntu2005@ubuntu:~$ 






ubuntu2005@ubuntu:~$ apt search ros-noetic
Sorting... Done
Full Text Search... Done
ros-noetic-abb-driver/focal 1.4.0-1focal.20230215.234845 amd64
  ROS-Industrial nodes for interfacing with ABB robot controllers.

ros-noetic-abb-driver-dbgsym/focal 1.4.0-1focal.20230215.234845 amd64
  debug symbols for ros-noetic-abb-driver

ros-noetic-abb-egm-msgs/focal 0.5.2-1focal.20220926.184335 amd64
  Provides ROS message definitions, representing Externally Guided Motion (EGM) data from ABB robot controllers.

ros-noetic-abb-rapid-msgs/focal 0.5.2-1focal.20220926.182609 amd64
  Provides ROS message definitions, representing RAPID data from ABB robot controllers.

ros-noetic-abb-rapid-sm-addin-msgs/focal 0.5.2-1focal.20220926.183002 amd64
  Provides ROS message and service definitions, representing interaction with ABB robot controllers using the RobotWare StateMachine Add-In.

ros-noetic-abb-robot-msgs/focal 0.5.2-1focal.20220926.184343 amd64
  Provides ROS message and service definitions, representing basic interaction with ABB robot controllers.

ros-noetic-ackermann-msgs/focal 1.0.2-1focal.20220926.184350 amd64
  ROS messages for robots using Ackermann steering.

ros-noetic-ackermann-steering-controller/focal 0.21.1-1focal.20230215.235437 amd64
  Controller for a steer drive mobile base.

ros-noetic-ackermann-steering-controller-dbgsym/focal 0.21.1-1focal.20230215.235437 amd64
  debug symbols for ros-noetic-ackermann-steering-controller

ros-noetic-actionlib/focal,now 1.14.0-1focal.20230215.221014 amd64 [installed,automatic]
  The actionlib stack provides a standardized interface for interfacing with preemptable tasks.

ros-noetic-actionlib-dbgsym/focal 1.14.0-1focal.20230215.221014 amd64
  debug symbols for ros-noetic-actionlib

ros-noetic-actionlib-lisp/focal 0.2.14-1focal.20230215.205510 amd64
  actionlib_lisp is a native implementation of the famous actionlib in Common Lisp.

ros-noetic-actionlib-msgs/focal,now 1.13.1-1focal.20220926.184702 amd64 [installed,automatic]
  actionlib_msgs defines the common messages to interact with an action server and an action client.

ros-noetic-actionlib-tools/focal 1.14.0-1focal.20230215.221556 amd64
  The actionlib_tools package

ros-noetic-actionlib-tutorials/focal,now 0.2.0-1focal.20230215.221331 amd64 [installed,automatic]
  The actionlib_tutorials package

ros-noetic-actionlib-tutorials-dbgsym/focal 0.2.0-1focal.20230215.221331 amd64
  debug symbols for ros-noetic-actionlib-tutorials

ros-noetic-agni-tf-tools/focal 0.1.6-1focal.20230216.011141 amd64
  This package provides a gui program as well as a rviz plugin to publish static transforms.

ros-noetic-agni-tf-tools-dbgsym/focal 0.1.6-1focal.20230216.011141 amd64
  debug symbols for ros-noetic-agni-tf-tools

ros-noetic-allocators/focal 1.0.25-1focal.20210517.131559 amd64
  Contains aligned allocation functions, as well as an STL-compatible AlignedAllocator class.

ros-noetic-amcl/focal 1.17.3-1focal.20230215.231533 amd64
  amcl is a probabilistic localization system for a robot moving in 2D.

ros-noetic-amcl-dbgsym/focal 1.17.3-1focal.20230215.231533 amd64
  debug symbols for ros-noetic-amcl

ros-noetic-angles/focal,now 1.9.13-1focal.20210727.062146 amd64 [installed,automatic]
  This package provides a set of simple math utilities to work with angles.

ros-noetic-app-manager/focal 1.3.0-1focal.20230215.220952 amd64
  app_manager
ros-noetic-ypspur-ros/focal 0.3.5-1focal.20230215.231636 amd64
  ROS wrapper for the mobile robot control platform YP-Spur

ros-noetic-ypspur-ros-dbgsym/focal 0.3.5-1focal.20230215.231636 amd64
  debug symbols for ros-noetic-ypspur-ros

ros-noetic-zbar-ros/focal 0.3.0-1focal.20230215.235905 amd64
  Lightweight ROS wrapper for Zbar barcode/qrcode reader library (http://zbar.sourceforge .net/)

ros-noetic-zbar-ros-dbgsym/focal 0.3.0-1focal.20230215.235905 amd64
  debug symbols for ros-noetic-zbar-ros

