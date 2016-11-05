
#Ardrone UAV

#How to Run on Terminal
run roscore
$roscore
run driver
$rosrun ardrone_autonomy ardrone_driver
or simulation
$roslaunch cvg_sim_gazebo ardrone_testworld.launch
run stateestimation node
$rosrun tum_ardrone drone_stateestimation
run autopilot node
$rosrun tum_ardrone drone_autopilot
run gui node
$rosrun tum_ardrone drone_gui

#How to Control Drone through Keyboard on GUI

w,a,s,d - Fly on horizontal
r,f 	- Fly Up and Down
q, e	- Control YAW
z, x	- TakeOff and Land

