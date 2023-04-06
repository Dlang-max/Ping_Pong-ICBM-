# PING_PONG_ROBOT_ICBM (Intercontinental Ball Machine)

This is the repo for Daniel Lang and Zach Boeck's Senior Capstone. 




![image](https://user-images.githubusercontent.com/59770928/224519787-24003ce6-15b4-4854-8212-5fde6178273f.png)


### March 11th, 2023

  At the time of writing this, we currently have a CAD model of our robot. 
Code has also been written to move the shoulder and elbow of our robot using human input from a controller.

### April 3rd, 2023

  Worked on adding code to control the arm both manually and automatically. I did this by using a motion profile 
provide by WPI for controlling an arm using relative encoders built into the Neo 550s. These encoders will slip
over time so I think we are going to add two limit switches to reset the encoder values of the shoulder and elbow
so we can accurately go to a set position. Tomorrow I'm going to work on our prediction code and integrate it with
our object detection model. I want to get displacement to the ping pong ball in meters. This will allow us to move our 
robot to a set position using a simple conversion. 

### April 4th, 2023

Links in this update will no longer work. Refer to April 5th update

  Created two new repositories. One contains code for calibrating a USB camera and the other contains code for pose
 estimation of a ping pong ball. This pose estimation will give us an x, y, and z translation from the ping pong ball to
 the camera. We will then predict where the ball will break the plane at the back of the ping pong table. Using 
 inverse kinematics we will determine what angles we need the joints of our arm to be at. Link to Calibration Repository:
 https://github.com/Dlang-max/Capstone_Camera_Calibration Link to first iteration of Distance Detection Repository: 
 https://github.com/Dlang-max/Distance_Detection This repository is bound to change. I'm also going to train a new object
 detection model for a ping pong ball because the one we are using right now isn't very accurate. 
 
### April 5th, 2023
 


