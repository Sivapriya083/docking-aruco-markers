# docking-aruco-markers

install ros dependencies and packages
create a ros workspace
bluid the necessary packages 
build the project using these command
------cd workspace
-------colcon build
       source install/setup.bash
 Run the simulation and nodes by starting Gazebo and the necessary nodes:
     
      - Implemented two launch files for testing we can use any one of them.
      - Start Gazebo simulation with:
       ros2 launch docking_robot gazebo_launch.py
      - Launch the detection and docking logic nodes with:
       ros2 launch docking_robot docking_launch.py
      
     
