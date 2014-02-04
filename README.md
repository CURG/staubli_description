# Staubli

A package for Staubli RX60L integration with [ROS-Industrial].

## Running

After installing ROS and "sourcing" the environment make sure you go to your catkin workspace and source the development code so that ROS knows where to find the files.
My catkin directory is ```/var/robot```

So I would run:

  ```source /var/robot/devel/setup.bash``` 

Then with that set up you can pull this repository to ```/var/robot/src/```
To display the robot, run the launch file with:

  ```roslaunch display.launch model:=urdf/staubli_rx60l.urdf gui:=true```

[ROS-Industrial]: http://www.ros.org/wiki/Industrial
