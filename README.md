# work_new
Here are my projects, mainly focusing on autonomous quadcopter flight and running object detection AI on cheap edge hardware.

My target hardware is Raspberry Pi Zero 2W. I plan on running an object detection model on it. To boost performance I'll use 1.58 bit quantization (a.k.a. BitNet), which also works for convolutions, and custom convolution kernels, written in C and optimized for CPU. 

After that I'll train a Reinforcement Learning Model to control the drone using Visual Inertial Odometry. 
