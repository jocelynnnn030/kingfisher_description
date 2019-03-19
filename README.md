# Kingfisher URDF

## Useful command to build the kingfisher model
* Convert xacro into urdf 
~~~~
rosrun xacro xacro urdf/robot_kingfisher.xacro > urdf/robot_kingfisher.urdf
~~~~

* Check the urdf model 
~~~~
check_urdf urdf/robot_kingfisher.urdf
~~~~

* Display urdf model in rviz
~~~~
roslaunch urdf_tutorial display.launch model:=urdf/robot_kingfisher.urdf
~~~~
