# Volume-Control-Using-Hands-Detection-System

Here, I have used simple python libraries to create a hand detection system 

  

Project Summary

In this project, you have created a hand-tracking application using MediaPipe and OpenCV that controls the system volume based on the distance between the thumb and index finger. You initialized a video capture object and set up a hand tracking detector using MediaPipe's Hands solution. You then defined the minimum and maximum volume values and set up the video capture dimensions. Inside the main loop, you captured video frames, found hand landmarks, and extracted the x and y coordinates of the thumb and index finger. You calculated the distance between these fingers and interpolated the volume value, setting the master volume level using the pycaw library. Additionally, you drew a circle on the image when the distance between the fingers was less than 50 units, and displayed the image using OpenCV. The program runs continuously until the user presses the 'q' key to quit.

ps: Install all the required libraries on cmd using pip install. 
