# Highway-traffic-simulation
Lane switching using deep learning

Increasing the input parameters helps. The patches behind parameter should also be taken into consideration. I figured this out a bit late when I saw that the car should drastically decrease it's speed to change the lane. 

With higher number of inputs the model takes a lot of time for training and during initial phase you would experience either the car is not moving or the car is not changing lanes.

<br/>
temporal window should be set to 0.

<br/>
Gamma parameter plays a big role in achieving higher speeds.
