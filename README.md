# Designing and programming user interface to control robotic movement

I've developed a control panel specifically for moving the base of the robot. The control panel allows movement in four directions: forward, backward, right, and left. Additionally, there is a dedicated button to stop movement.

The control panel operates as follows: When the forward button is pressed, the page sends the letter “F” to the database to store the corresponding value. Similarly, pressing the backward button sends the letter “B” to the database, the right button sends “R”, and the left button sends “L”. When the stop button is pressed, a message is displayed to inform the user that the robot has stopped moving.

Additionally, I've created another page that displays the current state of the robot's movement. This is achieved by retrieving the latest entry from the base table in the database, which indicates the direction in which the robot is currently moving.

I've made the web page responsive, to ensure a consistent user experience across various devices.

**_Note:_**
I've attached two videos to provide further clarification:
- Tutorial for controlling the robot base.
- Mobile web design (for optimal display on mobile screens).
