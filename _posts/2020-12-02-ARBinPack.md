---
layout: post
title:  "AR 3D Packing"
date:   2020-12-02 14:20:00 +0900
categories: portfolio
---
## Utilization of Depth Camera and Augmented Reality for Efficient 3D Box Packing Operation
<br>
### Background Problem
Container Loading Problem has been a common problem in Industrial Engineering field. Looking for optimal solution to pack the container can help decreasing the cost. However, the current solution is still addressed in old ways. I want everything is automatic from start to end. The loading process is not that simple actually. 

### Proposed Solution
The solution contains three parts:
1. Box Measurement
2. 3D Box Packing Calculation
3. AR Visualization

#### Box Measurement
In here, I utilized depth camera, such as Real Sense or Kinect, to measure the box size. Simply, when the box/ container is registered, the camera will measure Height, Length and Depth. This value will be used as input for the next process: Box Packing Algorithm. 

#### 3D Box Packing Calculation
In here, I apply 3d bin packing algorithm from papers, and implement it for backend calculation. The input is the size of boxes. The output of the calculation is coordinate. The box has 6 surfaces. The program will calculate the vertex coordinate for each surfaces.

#### AR Visualization
Once I got the coordinate, I visualize it with Augmented Reality. I used Unity and Vuforia to create the application. This AR visualization is made to help the workers packing the box container. So that the packing will be optimal as calculated.

Thanks to this project for giving me my Master degree~
