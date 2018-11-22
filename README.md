# QUADROTOR
micro controller used- Atmega32, Control Algorithm- PD, filter used- Kalman, Pre-requisites- None. No libraries were used.
Algorithm made for simple hover. Do-not use in aggressive trajectories.
Motor thrust= k1*(w^2), Motor torque= k2*(w^2).
w- angular velocity of motor or RPM, k1 and k2- constants that depend on the type of propeller used.
RPM rating is mentioned along with the motor as KV rating.
To determine k1, increase thrust till the quadrotor just lifts off the ground. Equate 4*k1*(w^2)= M*g where M is the weight of quadrotor.
k2 determines angular acceleration around yaw axis.
