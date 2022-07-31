# Inverse-Dynamics-Control-of-Robot-Manipulators
Determined Joint Torque Profiles of Manipulators holding a payload

## Instruction

Requires Peter Corke’s Robotics toolbox installed on your system (ver 10.4 or newer). 
See https://petercorke.com/toolboxes/robotics-toolbox/. 

Run the files:

`hw4problem1` <br>
`hw4problem2` <br>

Calculated the Spatial Inertia Matrix for each link. <br>
Simulates Robot falling under Gravity. <br>
Joint torques necessary to keep the robot at the home configuration is calculated. <br>
A Path is Generated in the Task Space and Converted into the Joint Space. <br>
Quintic Polynomial Trajectories are generated between setpoints and torque profiles are displated. <br>

To add a payload of 1kg to the end effector, uncomment lines 217-221 in h4problem1.
