---
layout: page
title: Segbot
description: A mobile robot that operates as a two-wheeled self-balancing robot or a three-wheeled differential-steering robot car. 
img: assets/img/Segbot_balance.jpg
importance: 2
category: #work
---

The Segbot is a mobile robot designed to operate as a three-wheeled differential-steering robot car or a two-wheeled self-balancing robot. The robot uses a Texas Instruments real-time microcontroller to interface with sensors and run the control algorithms that balance and steer the robot. Sensor fusion using Kalman filters is leveraged to improve measurements for balance control and navigation. I worked on this project with another graduate student for a course at the University of Illinois.

<div class="video-container">
    <iframe src="https://www.youtube.com/embed/g7M6W-UkW8s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen class="img-fluid rounded z-depth-1"> </iframe>
</div>
<div class="caption">
    A demonstration of the robot balancing on two wheels.
</div>

Further autonomy is added to the robot car by a base station that provides improved pose measurements to the robot. The robot navigates to ping-pong balls located by the base station's vision system and hits them out of the boundary defined by the four tags located on the floor.

<div class="video-container">
    <iframe src="https://www.youtube.com/embed/JvUbKMs5qAs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen class="img-fluid rounded z-depth-1"> </iframe>
</div>
<div class="caption">
    A demonstration of the robot car navigating to detected ping-pong balls and hitting them outside of the boundary area.
</div>

<div class="video-container">
    <iframe src="https://www.youtube.com/embed/QNWkfcSpWFU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen class="img-fluid rounded z-depth-1"> </iframe>
</div>
<div class="caption">
    A visualization of the base-station. Markers are labeled in white with their coordinates (X ,Y, theta) given in feet and radians. Circles are drawn around the tracked balls and are labeled with their coordinates [X, Y]. The green label indicates the target ball, while cyan and red represent balls inside and outside the boundary marked by the red polygon respectively.
</div>