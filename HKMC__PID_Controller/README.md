<!------ PROJECT TITLE ------>
<p align="center">
    <img src="readme_data/project_title.png" alt="title" width="1500"/>
</p> <br> <br>

<!------ WHAT ------>
<p align="center">
    <img src="readme_data/what.png" alt="what" width="600"/>
</p>

<p align="center"><h1>🎀 Essence of the Project</h1></p>
<p align='justify'>
At the core of this project is the implementation of a <strong>Proportional-Integral-Derivative (PID) Controller</strong>, a fundamental feedback mechanism critical in control systems for precise and stable motion planning. Designed for an autonomous systems, the PID Controller manages dynamic responses as the vehicle follows a designated path, adjusting steering based on real-time feedback to minimize deviation. This control is vital in various applications, from manufacturing robots requiring precise movement patterns to self-driving cars navigating complex environments.
</p>

<p align="center">
  <a href="https://www.youtube.com/watch?v=qgokbl5nwjg&t=1s">
    <img src="https://img.shields.io/badge/My Project Video-PID Motion Controller-blue" alt="Video" width="380" height="36"/>
  </a>
</p> <hr> <br> <br>

<!------ WHY ------>
<p align="center">
    <img src="readme_data/why.png" alt="why" width="600"/>
</p>

<p align="center"><h1>🎯 Project Vision</h1></p>
<p style="text-align: justify;">
The project vision for employing Proportional-Integral-Derivative (PID) controllers in autonomous systems is to enhance control precision in dynamic operational environments. The goal is to utilize the refined control capabilities of PID technology to ensure high accuracy and adaptability in response to environmental changes and system demands. This initiative seeks to demonstrate the critical role of PID controllers in improving the operational efficiency and reliability of complex, automated systems.
</p> <hr> <br> <br>

<!------ HOW ------>
<p align="center">
    <img src="readme_data/how.png" alt="How" width="600"/>
</p>

<p align="center"><h1>🪓Project Implementation</h1></p>
<p><h2>💠 Software Design & Tools </h2></p>
<p align='justify'>
This project utilizes a robust set of tools: Ubuntu and Linux for system stability, Python for scripting, ROS for robotics programming, Gazebo and RViz for simulation and visualization, and Numpy, SciPy, and Pandas for further data analysis of waypoints.
</p>
<p align='justify'>
<img src="https://img.shields.io/badge/Ubuntu-E95420.svg?&style=flat-square&logo=ubuntu&logoColor=white" alt="Ubuntu" style="height: 25px;"/> &nbsp;
<img src="https://img.shields.io/badge/Linux-FCC624.svg?&style=flat-square&logo=linux&logoColor=black" alt="Linux" style="height: 25px;"/> &nbsp;
<img src="https://img.shields.io/badge/Python-3776AB.svg?&style=flat-square&logo=python&logoColor=white" alt="Python" style="height: 25px;"/> &nbsp;
<img src="https://img.shields.io/badge/ROS-22314E.svg?&style=flat-square&logo=ros&logoColor=white" alt="ROS" style="height: 25px;"/> &nbsp;
<img src="https://img.shields.io/badge/Gazebo-000000.svg?&style=flat-square&logo=ros&logoColor=white" alt="Gazebo" style="height: 25px;"/>
<img src="https://img.shields.io/badge/RVIZ-000000.svg?&style=flat-square&logo=ros&logoColor=white" alt="Gazebo" style="height: 25px;"/> &nbsp;
<img src="https://img.shields.io/badge/Numpy-013243.svg?&style=flat-square&logo=numpy&logoColor=white" alt="Numpy" style="height: 25px;"/> &nbsp;
<img src="https://img.shields.io/badge/SciPy-654FF0?style=flat-square&logo=SciPy&logoColor=white" alt="SciPy" style="height: 25px;"/> &nbsp;
<img src="https://img.shields.io/badge/Pandas-150458.svg?&style=flat-square&logo=pandas&logoColor=white" alt="Pandas" style="height: 25px;"/> &nbsp;
<img src="https://img.shields.io/badge/VS%20Code-007ACC.svg?&style=flat-square&logo=visual-studio-code&logoColor=white" alt="VS Code" style="height: 25px;"/> &nbsp;
</p> <br>

<!------ Technical Terms ------>
<p align="center"><h2>💠 Project Technical Terms & Concept </h2></p>
<p align="center"><h3>▸ Working of PID Controllers</h3></p>
<p align='justify'>
The PID (Proportional-Integral-Derivative) controller is a control loop feedback mechanism widely used in industrial control systems. It adjusts the output to bring a process to its desired setpoint or target. Here’s a brief explanation of how each component works:
</p>
<p align="center">
  <img src="readme_data/pid_diagram.png" alt="Technical Term Images" width="900"/>
</p> <br>

<h3><strong> ▸ Proportional (P) Term: </strong></h3>
<p align='justify'>
This is the reactive part of the controller. It produces an output value that is proportional to the current error value - the difference between the desired setpoint and the current process variable. A higher proportional gain results in a larger output response to the error, which can improve the system's response time but also increase the risk of overshooting the setpoint.
</p> <br>

<h3><strong>  ▸ Integral (I) Term: </strong></h3>
<p align='justify'>
This component sums the error over time and integrates it with respect to the past errors. The integral term accelerates the movement of the process towards the setpoint and eliminates the residual steady-state error that occurs with a pure proportional controller. However, too much integral action can lead to instability and oscillations.
</p> <br>

<h3><strong>  ▸ Derivative (D) Term: </strong></h3>
<p align='justify'>
The derivative term predicts system behavior and thus can provide a damping effect. It is a measure of how quickly the process variable is changing and effectively slows down the output to prevent overshooting. It can improve stability and settle time.
</p> <br>

<p align='justify'>
The PID controller works by calculating an 'error value' as the difference between a measured process variable and a desired setpoint. The controller attempts to minimize the error by adjusting the process control inputs. The combination of these three terms provides control action designed to eliminate the error by adjusting process control variables such as the throttle, the steering angle, or the valve position in a system.
</p> <br>

<p align="center"><h3>▸ Why Do We Need to Tune a PID Controller</h3></p>
<p align='justify'>
▸ Tuning a PID controller is an essential step in any control system that employs feedback. Proper tuning ensures that the system responds to setpoint changes and disturbances rapidly and with minimal overshoot. Untuned or poorly tuned PID controllers can lead to inefficient operation, instability, excessive oscillation, or slow response times, all of which can affect the performance and safety of the controlled system. Effective tuning optimizes the control actions of the PID controller, ensuring it works in harmony with the dynamics of the process it is controlling.
    
▸ It is a delicate balance: the proportional term must be high enough to respond to changes, the integral term must correct any offset without causing instability, and the derivative term must predict and smooth the response. Without tuning, the controller cannot fulfill its role of maintaining the desired level of process control.
</p> <br>

<p align="center"><h3>▸ Advantages of PID Controller</h3></p>
<p align='justify'>
<ol>
<li>Precision Engineering: Essential for autonomous systems, PID controllers ensure precise navigation and positioning, reducing errors and enhancing accuracy in unpredictable environments.</li>
<li>Dynamic Stability: They provide stability in rapidly changing conditions, essential for autonomous vehicles to adapt to sudden obstacles or shifts in terrain, ensuring safe and reliable operation.</li>
<li>Adaptive Flexibility: With adaptable control parameters, PID controllers can be fine-tuned for various autonomous applications, from urban driving to off-road exploration, offering versatile performance.</li>
<li>Operational Efficiency: By optimizing system responses, PID controllers contribute to energy-efficient operation of autonomous vehicles, crucial for extending battery life and reducing environmental impact.</li>
<li>Design Simplicity: Their straightforward implementation makes PID controllers an accessible technology for enhancing the control systems of autonomous vehicles, even with limited engineering resources.</li>
<li>Universal Application: The wide applicability of PID controllers supports diverse functionalities in autonomous systems, from speed control to obstacle avoidance, proving their essential role in the future of transportation.</li>
</ol>
</p> <br>

<p align="left"><h3>▸ PID Tuning Methods</h3></p>
<p align='left'>
<ol>
<li>Manual Tuning</li>
<li>Trial and Error Tuning</li>
<li>Ziegler-Nichols Tuning Method</li>
<li>Cohen-Coon Tuning Method</li>
<li>Kappa-Tau Tuning Method</li>
</ol>
For a deeper understanding and guidance on PID tuning, consider visiting <a href="https://www.incatools.com/pid-tuning/pid-tuning-methods/">PID Tuning Methods</a>. This resource provides insights and practical advice on how to apply these methods to achieve a well-tuned control system.
</p> <br>

<!------ Deployment and Testing ------>
<p align="center"><h2>💠 Deployment and Testing </h2></p>
<p align="center">
  <img src="readme_data/project_obs_1.png" alt="Deployment and Testing Images" width="1500"/>
</p>

<p align='justify'>
<h3>1. Assign Waypoints and Visualize Them</h3>
Start by defining the desired path for the mobile robot through waypoints. Use visualization tools available in ROS, such as RViz, to plot these waypoints on a map. This helps in both planning the route and monitoring the robot's progress during execution.

<h3>2. Set Up PID Coefficients and Variables</h3>
Configure the PID controller with appropriate coefficients—proportional (Kp), integral (Ki), and derivative (Kd)—tailored to your specific robot. These values determine how the robot reacts to the difference between its current position and the waypoints (the error). You'll also need to set up vehicle-specific variables, such as maximum speed and turning angles.

<h3>3. Obtain Real-Time Odometry Information</h3>
Gather real-time odometry data from the robot's sensors. This data provides the robot's current position and orientation, which is crucial for calculating the error in the following steps.

<h3>4. Determine y-error Based on the Reference Trajectory</h3>
Calculate the lateral error (y-error) of the robot from its desired path. The y-error is the perpendicular distance from the robot to the closest point on the reference trajectory or the next waypoint.

<h3>5. Utilize Proportional Control</h3>
Apply proportional control to correct the robot's alignment with the path. The proportional term adjusts the robot's steering angle in proportion to the y-error, aiming to reduce the error over time.

<h3>6. Implement Integral Control</h3>
Use integral control to address any cumulative drift from the desired trajectory. This term sums the historical errors over time and applies corrections to eliminate bias and steady-state error.

<h3>7. Employ Derivative Control</h3>
Incorporate derivative control to anticipate future errors. It provides a damping force that reduces the rate of error change, preventing the robot from overshooting the path.

<h3>8. Combine P, I, D Responses</h3>
Combine the outputs of the P, I, and D terms to calculate the total steering command. The combined control signal is used to dynamically adjust the robot's steering to follow the path accurately.

<h3>9. Adjust the Drive Command</h3>
Adjust the robot's throttle or drive commands based on the control output to align its speed with the curvature of the path and current steering adjustments.

<h3>10. Steer the Robot</h3>
Finally, use the computed control inputs to steer the robot along the path. Monitor the robot's progress and continuously adjust the control signals to maintain a smooth and accurate trajectory.
</p>  <hr> <br> <br>

<!------ End Image ------>
<p align="center">
    <img src="readme_data/hk_quote.png" alt="endquote" width="1500"/>
</p>
