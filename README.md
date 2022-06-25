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

open the roboanalyzer software.
select the robot and its degrees of freedom.
change the values with the link lenght wherever necessary.
simulate the model for forward kinematics.
plot the graph between the link and the joints.
update the DH parameters of the link configuration and end effector configuration.



### SIMULATION 
 
 
 
 ![image](https://user-images.githubusercontent.com/89122599/175761988-5d9971de-8734-4d51-8e9b-48ddfb8d9339.png)

![image](https://user-images.githubusercontent.com/89122599/175762029-f4a298af-fc42-428d-a125-48bf5832282c.png)

![image](https://user-images.githubusercontent.com/89122599/175762040-507648a5-5e3c-4653-b799-351ad70f6ea6.png)

![image](https://user-images.githubusercontent.com/89122599/175762061-d907cb48-324e-4ade-b140-cded3155100c.png)

![image](https://user-images.githubusercontent.com/89122599/175762075-022c9eb3-6ad0-422b-a7f6-ac3a6993fd4c.png)

 
 ![image](https://user-images.githubusercontent.com/89122599/175762085-3711c4c9-892e-4dd0-bf4b-d6c2842a3adc.png)

 
  ![image](https://user-images.githubusercontent.com/89122599/175762093-cc85f5e2-2e93-4de8-b177-4117bfe993cd.png)

 
 
 
 
 
 
 
 
 
 
 

 
 














### RESULTS : 

Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
