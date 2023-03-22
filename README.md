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

