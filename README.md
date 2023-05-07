# SLAM_controller

Uses Particle filter to localize a robot configured in webots. The environmnet is simulated in webots as well. The controller is programmed using python.
Note: Webots must be installed from https://cyberbotics.com/doc/guide/installing-webots

# Motion Model

Sample odometry motion model.
    Arguments:
    x -- pose of the robot before moving [x, y, theta]
    u -- odometry reading obtained from the robot [rot1, rot2, trans]
    a -- noise parameters of the motion model [a1, a2, a3, a4]

# Sensor Model
generates sensor measurements.
update landmarks and calculate particle weights

Note: For mathematical formula derivation, refer:
https://docs.ufpr.br/~danielsantos/ProbabilisticRobotics.pdf

