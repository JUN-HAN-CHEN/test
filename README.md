# Introduction
The repo contains docker image for quick AMR simulator and robot_state_aggregator(Publish topic : \fleet_state). The detail of the message is described in "Message Interfaces.xlsx".

# Installation
* Install docker first
```sh
sudo apt-get install docker.io
```
* Load docker image
```sh
cd ros_docker_image_builder/
sudo docker load -i my_image.tar
```
Then you will see this in terminal
```sh
Loaded image: ros_techday_test:latest
```
# How to use
* Run the docker image
```sh
. start_ros.sh techday_test
```
* Open the byobu terminal
```sh
byobu
```
* Run the shell script
```sh
. demo.sh
```

