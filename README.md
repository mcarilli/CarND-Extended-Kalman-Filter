# Extended Kalman Filter Project Starter Code

[//]: # (Image References) 
[ekf_tracking]: ./ekf_tracking.png

This project implements an extended Kalman filter in C++. 

Input data consisting of laser measurements (given directly as
x and y positions, with some known uncertainty) and radar
measurements (given as radius, angle, and radial velocity 
relative to some fixed measurement site, with some known uncertainty)
are combined with a motion model to track a vehicle with much better
accuracy than the individual measurements alone allow.

The code presented here is designed to work with the
Udacity term 2 simulation executable, and so cannot be run standalone.
However, here's some example output.  

![Tracking car with EKF][ekf_tracking]

Lidar measurements are red circles.
Radar measurements are blue circles with an arrow pointing in the direction of the measured angle.
The green markers are the car's position as estimated by the Kalman filter.


