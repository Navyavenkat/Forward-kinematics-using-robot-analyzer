# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:

1.Open the roboanalyzer software.
2.Select the robot and the degrees of freedom.
3.Change the values with the link length wherever necessary.
4.Simulate the model for forward kinematics.
5.Plot the graph between the link and the joints.
6.Update the DH parameters of the link configuration and end effector configuration.





### SIMULATION 

4 DOF:

![image](https://user-images.githubusercontent.com/94165327/174299888-f52f88f9-1666-4d6a-9734-4e60b84c543e.png)

6 DOF:

![image](https://user-images.githubusercontent.com/94165327/174300000-4421b0a5-4b7e-45b7-ac76-11b337d4e8e4.png)

 ### EE COFIGURARTION
 
 4 DOF:
 
 ![image](https://user-images.githubusercontent.com/94165327/174300204-2b9e0c79-bd6b-461e-b17c-fb7392320a7d.png)

 
 6 DOF:
 
 ![image](https://user-images.githubusercontent.com/94165327/174300271-50236ecc-842f-408e-9f74-92fef1f132d8.png)

 
 ### PLOT 
 
 4 DOF:
 
 ![image](https://user-images.githubusercontent.com/94165327/174300339-1c947a8e-bb6f-4552-a709-e8404ee8e9d0.png)

 6 DOF:
 
 ![image](https://user-images.githubusercontent.com/94165327/174300419-1e4524fe-6ae6-4076-bce7-922e61700689.png)

 

### RESULTS :  

Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted..
