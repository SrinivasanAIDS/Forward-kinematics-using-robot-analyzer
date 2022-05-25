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
1) open the roboanalyzer software.
2) select the robot and its degrees of freedom.
3) change the values with the link lenght wherever necessary.
4) simulate the model for forward kinematics.
5) plot the graph between the link and the joints.
6) update the DH parameters of the link configuration and end effector configuration.

### SIMULATION 

#### 6 DOF
#### Screenshot
![image](https://user-images.githubusercontent.com/103049243/170276939-6c61fcb8-92fc-48d0-855c-af3f95dd8c90.png)

#### 4 DOF
#### Screenshot
![image](https://user-images.githubusercontent.com/103049243/170277180-b2afcdaa-c839-4248-b46b-994d1bc15678.png)

### PLOT 
 
#### 6 DOF
![image](https://user-images.githubusercontent.com/103049243/170277314-0fdedd40-68fa-4478-b632-beafec656c89.png)
![image](https://user-images.githubusercontent.com/103049243/170277385-95ef6136-741c-4d7a-9f6e-0305e648b25e.png)
![image](https://user-images.githubusercontent.com/103049243/170277464-3a38968d-485c-47b1-9224-3659ff4cd7f6.png)

#### 4 DOF
![image](https://user-images.githubusercontent.com/103049243/170277557-61e5af69-2fe6-481a-b923-34635ec210a8.png)
![image](https://user-images.githubusercontent.com/103049243/170277660-bb4cb27d-882e-4bb6-84e4-47be8709b2bd.png)
![image](https://user-images.githubusercontent.com/103049243/170277735-7b8ee0d8-b20c-4a15-b00a-fbe66fa6c140.png)

### RESULTS :  
Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
