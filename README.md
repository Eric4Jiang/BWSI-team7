# BWSI-team7
Code for Team 7, racecar-66 during BWSI Summer 2017!

## Installation
`cd ~/`

`git clone https://github.com/Eric4Jiang/BWSI-team7.git`

## AR tag follower
`cd ~/BWSI-team7`

`roslaunch BWSI-team7 ar_following.launch`

## Run BWSI-2017 Final Course
`cd ~/BWSI-team7`

Launch zed camera, teleop, and ar_localize

`roslaunch BWSI-team7 g0_fast.launch`

Run state controller

`cd src/state_machine`

`python state_controller.py`

