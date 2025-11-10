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
<img width="1046" height="679" alt="Screenshot 2025-11-10 161215" src="https://github.com/user-attachments/assets/7e2ef3ac-6a03-4570-bcaf-cb88d2f09df3" />
<img width="1054" height="690" alt="Screenshot 2025-11-10 161303" src="https://github.com/user-attachments/assets/0c21e251-b9ff-40c6-82a6-353c954320be" />
<img width="1017" height="667" alt="Screenshot 2025-11-10 161253" src="https://github.com/user-attachments/assets/8b42d35c-bb03-44e9-b35e-24184ec8556d" />
<img width="1052" height="696" alt="Screenshot 2025-11-10 161239" src="https://github.com/user-attachments/assets/d98628e3-adf4-4fa4-9e70-7ad5f6590895" />
<img width="1053" height="682" alt="Screenshot 2025-11-10 161226" src="https://github.com/user-attachments/assets/59605e0d-0927-465a-bc32-f8d3da07b39d" />
<img width="1047" height="745" alt="Screenshot 2025-11-10 161331" src="https://github.com/user-attachments/assets/4504751e-77a5-4424-b139-263892164def" />
<img width="1048" height="741" alt="Screenshot 2025-11-10 161318" src="https://github.com/user-attachments/assets/7288d549-c5f5-442a-bdb6-6c9b64cc6128" />



### Results 
Thus,a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio executed.


 
