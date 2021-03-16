### CSCI_5551 Project Code

This readme is a temporary file for us to communicate progress and such within our place in the repo.
So far all we need to worry about is getting it up and running.

Steps to do so:

Download ROS to your computer, or use school computer. Currently functioning with ROS Melodic, although we
could likely get it to work with Noetic as well.
```
  sudo apt install ros-melodic-*
```
Once that is installed, make sure its working by running
```
  roscore
```
And if that is running successfully, we can move on to this repo.

TO GET DEMO TO WORK:

1. Create a catkin workspace in a directory of your choice on your computer.
2. Add the repo to the src/ folder of your workspace. Directory should look like:
```
    catkin_ws/src/moveo_ros/
```
3. Successfully build repo using
```
    catkin build
```
May need to download additional packages to get this command to work.

Add this command to your ~/.bashrc file:

    source ~/path-to-your-workspace/catkin_ws/devel/setup.bash

Then run the demo using the README from the repo. Command used is
```
    roslaunch moveo_moveit_config demo.launch
```
This should take you to the Rviz simulator, where you can now play around with the robot.
Make sure to check the "Allow Approximate IK Solutions" checkbox before beginning.

Great, the demo is working! Now what?

------------------------------------------------------------------------------------------------------

TODO:


CURRENT PROGRESS:
