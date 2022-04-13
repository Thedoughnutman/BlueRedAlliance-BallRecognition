# BlueRedAlliance-BallRecognition
My version has no use of contours. The ball is found by masking the RGB values to highlight blue/ red as the brightest pixels and then averaging the pixel positions.

### PROBLEM 
Without basing off of outlines-- the method I am using will also detect other random colors. My current plan is to dynamically set the camera's brightness at startup and then get a flashlight to light the area in front of it up. Knowing the inverse square law-- the shining light will get more dim as it gets farther away. Since the colored balls are closest to the light souce, it allows the camera to only detect the colored balls near it first with good accuracy.

Tested on a Dual Core Thinkpad T430 using anaconda3 with Python3 ipykernel in Jupyter Notebook
