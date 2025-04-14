# Control Strategies for Trajectory Tracking - Comparative Study

This project presents a comparative study of multiple
control strategies for trajectory tracking in autonomous
mobile robots. Leveraging 2D LIDAR-based SLAM for
trajectory generation, we evaluate the performance of
six controllers—PID, PD, MPC, Fast MPC, LQR, and
LQG—under varying speed conditions. The analysis
focuses on tracking accuracy using cross track error as
the key performance metric. Our findings offer insights
into the trade-offs between classical and optimal control
methods, highlighting their respective strengths, limita-
tions, and suitability for real-world navigation tasks.


## 🚀 Features

- ✅ 2D Lidar SLAM generated trajectory from a dataset
- ✅ Robot state update using kinematic equations (unicycle model)
- ✅ PID and PD controller with anti-windup and heading-based speed scaling
- ✅ MPC controller with discrete control search over prediction horizon
- ✅ Fast MPC version optimized for speed and responsiveness
- ✅ Fully integrated Simulink simulation environment
- ✅ Visualization and export of XY trajectory plots
