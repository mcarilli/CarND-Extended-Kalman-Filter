# CarND-Extended-Kalman-Filter
Udacity self-driving car nanodegree Term 2 Project 1 solution:  Extended Kalman Filter in C++.

Takes a random sequence of noisy laser measurements 
(given directly as x and y positions, with some known level of uncertainty) 
and radar measurements (given as a radius, angle, and radial velocity relative 
to some fixed measurement site, with some known level of uncertainty)
and combines them with a motion model to track the car's actual position, achieving much 
greater accuracy than the noisy individual measurements permit.

Unfortunately the code presented here is designed to work with the Udacity term 2 simulator executable, so
it cannot be run standalone.  However, here's some sample results:
