# UPenn Bird Recording project root repository

This repository contains the relevant ros packages as submodules.
Tested on Ubuntu 16.04 LTS / ROS kinetic.

Maintainer: Bernd Pfrommer (pfrommer@seas.upenn.edu)

## Installation

Prerequisite: working installation of ROS kinetic
(http://wiki.ros.org/kinetic/Installation/Ubuntu). If this is a new
user, don't forget to run "rosdep update" and update the .bashrc file.

	cd Documents
	git clone https://github.com/daniilidis-group/birds.git
	cd birds
	git submodule init
	git submodule update
	catkin build

## Using

Overlay the ros packages:

	. devel/setup.bash
	roscd bird_recording/launch

and see the bird_recording package for further instructions
	