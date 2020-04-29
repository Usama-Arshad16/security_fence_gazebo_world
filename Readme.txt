Easy method to open the world.

1. Place this package in your desired directory.
2. Open "security_fence" folder.
3. Click right and click on "Open in terminal"
4. Write the following command. "gazebo security_fence_world"
5. Your world will be open.

2nd Method
If you have ros in your PC then you can open the urdf file of this world.
7. Place the "security_fence_world" package in src folder of your catkin_ws.
8. Open terminal and use these following commands
	cd catkin_ws 
	catkin_make
	source devel/setup.bash
	roslaunch security_fence_world fence.launch

9. The world will be open.