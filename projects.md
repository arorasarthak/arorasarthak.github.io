## Projects

### Deep Electromyogram Gesture Recognition                                  
```markdown
Python, sklearn, TensorFlow, MATLAB
```
Performed real time gesture recognition of EMG signal data using Deep Neural Nets and Support Vector Machine. 
The EMG time series data was subjected to several preprocessing and filtering techniques such as the application of FFT, 
Wavelet Transforms. Some bespoke data augmentation techniques such as data rolling were also applied. 
The resulting system gesture recognition system was able to achieve 95% test accuracy.

______
&nbsp;
&nbsp;

### Indoor Navigation Ackerman Robot
```markdown
Ubuntu Core, ROS, Python, C++
```
An autonomous ackermann steering robot was designed and implemented using a 1:10 RC car chassis, Arduino Mega,
Raspberry PI, 2D LiDAR, 9 DoF IMU & an ESC. 2D mapping was done by using gmapping & hector mapping.
Localization was achieved using adaptive monte carlo localization. Path planning was implemented using an
adaptive trajectory controller. Odometry was achieved by fusing LiDAR & IMU data using EKF.

[Report](https://drive.google.com/open?id=1VRlRwUEt1IOqurRjTZPI8RPevrMzf5Pv)

[![Video](https://img.youtube.com/vi/AJJj-5kTbgY/0.jpg)](https://www.youtube.com/watch?v=AJJj-5kTbgY "Video")

Click on the image to watch the video!

______
&nbsp;
&nbsp;


### North Following Autonomous Differential Drive
```markdown
Arduino, C++
```
A differential drive wheel base was used to implement vector field histograms as a local planner along 
with a magnetometer. A time-of-flight sensor was panned to achieve all the distances in field-of-view. 
The odometry was achieved with an IMU and encoders. Ultimately, a camera was used for target/goal recognition. 
The robot would drive towards north direction and stop at a red colored target.

[Report](https://drive.google.com/open?id=1iirYKXWcU3Hmw-NRIQIR0--KPjniWaK9)    

[![Video](https://img.youtube.com/vi/jdVLMRE6gJY/0.jpg)](https://www.youtube.com/watch?v=jdVLMRE6gJY "Video")

Click on the image to watch the video!

______
&nbsp;
&nbsp;


### Deep Attention based Character Recognition using Spatial Transformers Nets
```markdown
Python, TensorFlow
```
Compared the performance of 2D Convolutional Layers vs. Spatial Transformer Layers on Devanagari and Bengali Script Datasets.
A new approach was proposed to perform character recognition on script characters from the Indian subcontinent. 
The resulting system achieved a test accuracy of 98% by beating the previous state of the art method.

[Report](https://drive.google.com/open?id=1pcSsBqHPw3vPDB9H07hbWmwNF7Svtf0q)

______
&nbsp;
&nbsp;


### Plugin Development for CoppeliaSim/VREP for creating low latency digital twin setup for Universal Robots
```markdown
C++, Lua
```
A plugin for CoppeliaSim/VREP was developed to directly interact with Universal Robots hardware over their custom 
protocol called Real Time Data Exchange (RTDE). The [RTDE interface developed at SDU was used](https://sdurobotics.gitlab.io/ur_rtde) to develop this plugin. The plugin works using a Lua frontend. The robot is 
programmed using the URScript programming language, allowing the user to setup a Simulation-in-Loop scenario or create a 
simulation inside CoppeliaSim/VREP like Gazebo.

[![Video](https://img.youtube.com/vi/SrnnDEN5O3I/0.jpg)](https://youtu.be/SrnnDEN5O3I "Video")

Click on the image to watch the video!

______
&nbsp;
&nbsp;


### Exploration of Autocorrelation and Power Spectral Characteristics of a Low-Pass Random Process
```markdown
MATLAB
```
An exploratory data analysis project was done as a part of graduate coursework in Random Signals and Noise.

[Report](https://drive.google.com/open?id=1Qw-WtVVEkUPZthruNtmrdPY4QebIL1b6)
