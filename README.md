# robot_control_gui
First step can follow the steps below to install the necessary simulation packages of TurtleBot3.
1) Go to the source folder of the workspace (cd catkin_ws/src)
2) Copy the codes below into the terminal
git clone https://github.com/ROBOTIS-GIT/turtlebot3_msgs.git
git clone https://github.com/ROBOTIS-GIT/turtlebot3.git -b melodic-devel   
(melodic-noetic-kinetic Your choice!!!)
git clone https://github.com/ROBOTIS-GIT/turtlebot3_simulations.git -b melodic-devel
3) Go back to the workspace (cd ~/catkin_ws) and compile (catkin_make)

Later on 
1) Go to catkin_ws/src 
2) Write this https://github.com/barisdundar/robot_control_gui.git
3) Go back to the workspace (cd ~/catkin_ws) and compile (catkin_make)

Later on 
1) Open Terminal
2) roslaunch turtlebot3_gazebo turtlebot3_empty_world.launch 
3) Open new Terminal

4)Type this in the terminal you just opened rosrun catkin_ws 




This Project Picture


![robotic](https://user-images.githubusercontent.com/64458945/209945801-3b92c47b-60ad-46b5-815c-3197e1a20fa1.png)
