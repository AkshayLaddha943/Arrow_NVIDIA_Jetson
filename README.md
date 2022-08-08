<img src="https://github.com/AkshayLaddha943/Arrow_SensorFusion_turtlebot3/blob/main/Arrow.png" align="right" height="200" width="200" alt="header pic"/>

# Arrow_NVIDIA_Jetson

This repository encapsulates the ROS workspace containing the necessary packages and program nodes to simulate a simple turtlebot3 and further performing SLAM on turtlebot3 whilst adding noise to wheel odometry sensor motion model and IMU sensor. It also includes the results folder containing images and videos of simulation of turtlebot3 for different situations and a documentation as part of my Internship with Arrow Electronics (eInfochips).


## Pre-requisites

- [NVIDIA Jetson Nano Developer Kit](https://www.amazon.com/NVIDIA-Jetson-Nano-Developer-945-13450-0000-100/dp/B084DSDDLT?&linkCode=sl1&tag=visahuntercom-20&linkId=99ff9fe802cbd2869de7aea4cd737eb3&language=en_US&ref_=as_li_ss_tl)

- [SD/Micro SD Card Reader with Standard USB Connector](https://www.amazon.com/s?k=SD%2FMicro+SD+Card+Reader+with+Standard+USB+Connector&language=en_US&linkCode=sl2&linkId=557f29854731bf95060ad3bd7fb56455&tag=visahuntercom-20&ref=as_li_ss_tl)

- [Raspi Camera 5MP](https://www.raspberrypi.com/products/camera-module-v2/)

- [Micro-controller(STM32)](https://www.amazon.com/STM32-Nucleo-Development-STM32F446RE-NUCLEO-F446RE/dp/B01I8XLEM8/ref=asc_df_B01I8XLEM8/?tag=hyprod-20&linkCode=df0&hvadid=312363638090&hvpos=&hvnetw=g&hvrand=9282893380648728051&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9001847&hvtargid=pla-585245210378&psc=1)


## Table of Contents

* [Setting up NVIDIA Jetson](https://automaticaddison.com/how-to-set-up-the-nvidia-jetson-nano-developer-kit/)

 
 
## Install and Verify relevant packages

```
sudo apt-get install python3
sudo apt-get install gedit

```
Verify if the package has been correctly installed

```
which python3

#output should be
/usr/bin/python3

```
In a new terminal,

```
sudo apt-get update
sudo apt-get -y upgrade
sudo apt-get install -y python3-pip

#To install any specific package in the future
pip3 install package_name
