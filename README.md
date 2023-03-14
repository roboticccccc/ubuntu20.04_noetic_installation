# Ubuntu20.04_Noetic_installation
# Instructions and details for installing Ros-Noetic on Ubuntu20.04.

1.安装VMware Workstation Pro

2.下载并安装Ubuntu20.04

3.安装git与curl

4.安装Pigcha代理并打开代理

5.添加源

6.添加密钥

7.更新包索引
# sudo apt update

8.安装Noetic
# sudo apt install ros-noetic-desktop-full

9.通过ipaddress更新hosts文件，将151.101.84.133 raw.githubusercontent.com添加到文件末尾，ip用最新的替换
# cd /etc
# sudo gedit hosts

9.更新依赖
# sudo rosdep init
# sudo rosdep update

10.设置环境
# echo "source /opt/ros/noetic/setup.bash" >> ~/.bashrc
# source ~/.bashrc
