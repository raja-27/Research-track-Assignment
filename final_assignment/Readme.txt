#Name: Raja taha hussain
reg no: s5046306

The  software architecturefor the control of the robot in the environment. The software willrelyon the move_baseand gmappingpackages for localizingthe robot and plan the motion.The architectureshouldbe ableto getthe user request, and letthe robot executeone of the following behaviors(dependingon the user’sinput):-1) moverandomlyin the environment, by choosing1 out of 6 possibletarget positions:[(-4,-3);(-4,2);(-4,7);(5,-7);(5,-3);(5,1)], implementinga random position service asin the assignment1-2) directlyaskthe user for the nexttarget position (checking thatthe position isone of the possiblesix) and reachit-3) start following the externalwalls-4) stop in the last position

## Instructions about how to run the code
                 ASSIGNMENT 2
                 
roslaunch final_assignment simulation_gmapping.launch (to turn on Gazebo and rviz)
                 
roslaunch final_assignment move_base.launch
                 
rosrun final_assignment wall_follow_service_m.py
               
rosrun my_srv finalassignment_server
                    
rosrun final_assignment ask_user_interface.py
                  
 /rosrun rqt_graph rqt_graph/
