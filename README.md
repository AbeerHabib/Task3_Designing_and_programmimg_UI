# Robot-base-control-panel
Control the movement of the robot base, or generally allow the robot to move forward, backward, right and left, and store those values in the database.

________________________________________________________________________________________________________________________________________________________________


I have completed on the previous control panel page by creating another control panel for moving the base. To move the base, we have four directions for the robot to move which are, forward, backward, right, left, and a button to stop moving. 
**How does this control panel work?** When the forward button is pressed, the page sends the letter “F” to the database to store the value, and when the backward button is pressed, the page sends the letter “B” to the database to store the value, and when the right button is pressed, the page sends the letter “R” to the database to store the value. And when the left button is pressed, the page sends the letter “L” to the database to store the value, while when the stop button is pressed, a message appears to the user that the robot has stopped moving.

Also, I created another page to display the current state of the robot's movement, I did this by retrieving the last row of the base table, this means that the robot is moving in the same direction as that returned value.

Also, I made the web page compatible with all devices, including mobile devices, so that the spacing between the page elements remains the same on a computer or any other mobile device.

**__Notice:__**
I have attached two videos to clarify:
- Robot base control tutorial.
- Mobile web design (for displaying the page on the mobile screen).
