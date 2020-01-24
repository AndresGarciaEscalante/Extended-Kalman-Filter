## Project Description
### Sensor Fusion
Merge sensors measurements to obtain a more robust and accurate value. This allows the final value to take advantage of each sensor:

![](Images/robot_model.png)

### Turtlebot Package:
Provides a Turtlebot in a gazebo environment surrounded by objects.

![](Images/Turtlebot_Package.png)

For more information about the package please refer to:
[Turtlebot Package](https://github.com/turtlebot/turtlebot_simulator)

### Robot Pose EKF Package:
Applies **Sensor Fusion** to the robot's sensors measurements to estimate its pose
to by using the **Extended Kalman Filter**. In this case to interface the **Turtlebot Package** with the **Robo Pose EKF Package** the following corrections were made: 

![](Images/TP_RPE.png)

For more information about the package please refer to:
[Robot Pose EKF Package](https://github.com/udacity/robot_pose_ekf )

### Odometry to Trajectory Package:
Allows to generate the Unfiltered and Filtered Pose Trajectories of the Robot, as shown in the following image:

![](Images/Odom_Package.png)

For more information about the package please refer to:
[Odometry to Trajectory Package](https://github.com/udacity/odom_to_trajectory )

### Teleop Package:
Allows to control the movement of the robot with keyboards.

For more information about the package please refer to:
[Teleop Package](https://github.com/turtlebot/turtlebot)

## Project Outcome
The main objective of the project is to control the movement of the turtlebot by using the keyboards in the Gazebo environment and compare the **Unfiltered and Filtered Pose Trajectories**. Please check the full video:

[ExtendedKalmanFilterProject](https://youtu.be/GlAfpySXPgs)
