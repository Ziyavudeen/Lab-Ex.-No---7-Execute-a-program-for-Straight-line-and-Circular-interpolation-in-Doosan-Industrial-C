# Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.

### PROGRAM:

![image](https://user-images.githubusercontent.com/120120067/206686945-a521db6d-7f82-44c6-818b-fd36a18507be.png)

![image](https://user-images.githubusercontent.com/120120067/206687056-229cd4b8-5a5d-44e0-813f-9e11b39d108e.png)

![image](https://user-images.githubusercontent.com/120120067/206687106-5f81875a-463e-48f6-b7ba-73226fb82fad.png)

![image](https://user-images.githubusercontent.com/120120067/206687154-19dd53b1-8bde-4ea3-95d6-f7f7dc3cc158.png)

![image](https://user-images.githubusercontent.com/120120067/206687230-c1dc4930-cd55-4f53-bf42-6fbc67952bae.png)

### Linear Interpolation:

![image](https://user-images.githubusercontent.com/120120067/206687344-07b579f6-0368-466b-8358-54477ab9ace3.png)

### Circular Interpolation:

![image](https://user-images.githubusercontent.com/120120067/206687430-c2a9d152-6bac-4803-812f-d9830cad4e9d.png)











### output

Linear Interpolation:

![image](https://user-images.githubusercontent.com/120120067/206687710-55455c00-2dc6-4bc5-9272-3e9b30db214d.png)

Circular Interpolation:

![image](https://user-images.githubusercontent.com/120120067/206687762-6ecd161a-4075-4509-8b00-59a273f98874.png)

### Results :
A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.



 
