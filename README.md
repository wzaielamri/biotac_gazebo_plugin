# Gazebo plug-in for simulating BioTac tactile sensors

## Overview
- This repository contains a Gazebo plug-in for simulating BioTac tactile sensors. 
- The plug-in publishes ROS messages containing simulated electrode and pressure sensor readings as if they were generated by real BioTac sensors. 
- The sensor outputs are simulated using an artificial neural network. 
- Example projects, training scripts, and a pretrained sensor model are included. 

## Installation
- Clone this reposity
- If you want to run the demos: get the Shadow hand packages and their dependencies
- If you want to train the plug-in yourself instead of using a pretrained model, get Keras, Tensorflow, Apriltags, and the Shadow hand packages

## Running the demos
- Launch a simulation environment (eg. `roslaunch sim_biotac_motorhand sim_biotac_motorhand_1.launch`, or `roslaunch sim_biotac_motorhand sim_biotac_motorhand_2.launch`, or `roslaunch sim_biotac_motorhand ur5_motorhand.launch`)
- Run one of the tests (eg. `rosrun sim_biotac_motorhand move_finger_1`, or `rosrun sim_biotac_motorhand move_finger_2`, or `rosrun sim_biotac_motorhand three_pod_grasp`)
