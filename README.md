# ROS2 Docker Documentation

## Tested
* windows/WSL
    * subscriber and publisher nodes (language agnostic)
    * turtlesim gui app
## TO-DO
* commit dockerfile / compose file
* test on bare-metal linux or linux vm
* test on macOS
* make sure gui apps run on linux and macOS

## What is Robot Operating System (ROS)?
The Robot Operating System (ROS) is an open-source robotics middleware suite that provides a set of software frameworks for robot software development. Note: ROS1 and ROS2 are not inter-operatable.
## ROS Structure
### Nodes
Low-level computational process
### Parameters
Node runtime shared multi-variate dictionary
### Topics
A named bus (pub/sub) over which nodes broadcast and receive messages (one-way); i.e. a messaging infrastructure
### Services
Request/response synchronous interaction with a node
### Actions
Asynchronous goal exectution of a server and goal requests of a client.
## What is Docker?
Docker is a platform that uses OS-level virtualization to deliver software in containers. It automates the deployment of applications in lightweight containers, isolating them from one another and bundling their own software, libraries, and configuration files. These containers can run on Linux, Windows, or macOS.
## What does this repo do?
This repo will setup a docker container based on the ROS2 Humble distribution. The humble distribution is supported until May 2027 as opposed to the most recent long-term support (LTS) version of ROS2 Iron which ends in November 2024.
## Installation Guide
### Pre-requisites
* Latest installation of docker
* For Windows users, WSL2 (Ubuntu) and a Windows version compatible with WSLg (for GUI apps)
    * Enable WSL integration within Docker Desktop settings

To-do
## Additional Resources
To-do

* Docker: https://www.docker.com/
* ROS Site: https://www.ros.org/
* ROS Docs: https://docs.ros.org/
