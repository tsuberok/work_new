# work_new
Here are my projects, mainly focusing on autonomous quadcopter flight and running object detection AI on cheap edge hardware.

My target hardware is Raspberry Pi Zero 2W. I plan on running an object detection model on it. To boost performance I'll use 1.58 bit quantization (a.k.a. BitNet), which also works for convolutions, and custom depthwise separable convolution kernels, written in C and optimized for CPU. 

After that I'll train a Reinforcement Learning Model to control the drone using Visual Inertial Odometry. 

Work_new repo contains a kaggle notebook where I train a modified YOLO v12 nano model. 1.58 bit quantization requires training a model form scratch. 

In the yolov12 repo I have a fork of yolov12 which I modify to be able to to 1.58 bit convolutions. 
