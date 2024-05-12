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
The Pure Pursuit Controller, a Path Tracking Algorithm, is frequently used in robotics and autonomous systems to autonomously follow a predefined path. This capability is critical in scenarios requiring accuracy and adaptability, such as industrial robots navigating factory floors, drones maneuvering through environments, or autonomous cars traveling on roads. The algorithm’s robustness is especially beneficial in agricultural automation, where precise path following is essential for efficient planting and harvesting.
</p>

<p align="center">
  <a href="https://www.youtube.com/watch?v=qgokbl5nwjg&t=1s">
    <img src="https://img.shields.io/badge/My Project Video-Pure Pursuit Controller-blue" alt="Video" width="370" height="35"/>
  </a>
</p> <hr> <br> <br>

<!------ WHY ------>
<p align="center">
    <img src="readme_data/why.png" alt="why" width="600"/>
</p>

<p align="center"><h1>🎯 Project Vision</h1></p>
<p style="text-align: justify;">
Project Vision focuses on leveraging the Pure Pursuit algorithm to achieve precise and adaptive path tracking in complex autonomous systems. The aim is to optimize path fidelity and maneuverability across a variety of operational environments, enhancing the efficiency and safety of autonomous vehicles and mobile robotics. By refining the algorithm’s response to dynamic conditions and obstacles, the project seeks to set a new benchmark in the reliability and precision of automated navigation systems.
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
<p align="center"><h2>💠 Project Technical Terms & Concepts </h2></p>
<p align="center"><h3>▸ What are path tracking algorithms?</h3></p>
<p style="text-align: justify;">
Path tracking algorithms are a set of computational techniques used in autonomous vehicle systems to determine and follow a defined path from one point to another. These algorithms calculate the best trajectory for a vehicle to travel, ensuring it remains on course while adjusting to any changes or obstacles in the environment.
</p> <br>

<p align="center"><h3>▸ What is look ahead point in pure pursuit controller?</h3></p>
<p style="text-align: justify;">
In the Pure Pursuit controller, the look ahead point is a future point on the path that the vehicle aims to follow. It is dynamically calculated based on the current position and orientation of the vehicle, helping guide the steering direction to smoothly navigate the path.
</p> <br>

<p align="center"><h3>▸ What is look ahead distance in pure pursuit controller?</h3></p>
<p style="text-align: justify;">
Look ahead distance in the Pure Pursuit controller refers to the fixed or variable distance ahead of the current position of the vehicle at which the look ahead point is set. This distance is crucial as it influences the responsiveness and curvature of the vehicle's path, affecting how sharply the vehicle can turn and adapt to the path.
</p> <br>

<p align="center"><h3>▸ Is look ahead that important?</h3></p>
<p style="text-align: justify;">
Yes, look ahead is extremely important in path tracking algorithms like the Pure Pursuit controller. It directly impacts the smoothness and accuracy of the path tracking, particularly in how the vehicle anticipates and responds to curves and changes in the path, thus enhancing overall navigation safety and efficiency.
</p> <br>

<p align="center"><h3>▸ How to perform Pure Pursuit faster?</h3></p>
<p style="text-align: justify;">
To perform Pure Pursuit faster, consider using efficient data structures like Binary Search Trees (BST) or employing advanced searching algorithms for quicker waypoint look-up. These techniques can significantly reduce the computational overhead and enhance the response time of the path tracking process.
</p> <br>

<p align="center"><h3>▸ Advantages of Pure Pursuit Controller</h3></p>
<p align='justify'>
<ol>
<li>Simplicity: The algorithm's inherent simplicity belies its sophisticated underpinnings, making it an ideal candidate for integration into autonomous navigational systems where clarity of design is paramount for reliability and maintainability.</li>
<li>Reactivity: Its reactive nature allows for robust adaptability to environmental variations and dynamic obstacles, a critical feature for autonomous systems in variable terrains and unpredictable urban landscapes.</li>
<li>Smoothness: Pure Pursuit's circular arc-based path generation ensures kinematic consistency, delivering smooth motion profiles that are essential for the operational integrity of high-speed autonomous vehicles and sensitive robotic equipment.</li>
<li>Versatility: The algorithm's modular design facilitates seamless integration with various vehicular architectures, from differential drive robots to Ackermann steering models, proving its versatility across multiple robotic platforms.</li>
<li>Predictability: The deterministic nature of the Pure Pursuit controller provides a predictable control scheme, crucial for ensuring the safety and reliability of autonomous systems in regulated environments such as automated manufacturing and urban transport.</li>
</ol>
</p> <br>

<!------ Deployment and Testing ------>
<p align="center"><h2>💠 Deployment and Testing </h2></p>
<p align='justify'>
The accompanying images serve as a detailed guide to the Pure Pursuit controller, illustrating its functionality and key theories. Whether you prefer a visual walkthrough or a dynamic video demonstration, this content is designed to facilitate a deeper grasp of deploying Pure Pursuit in real-world scenarios.
</p>

<p align="center">
  <img src="readme_data/project_obs_1.png" alt="Observation Image" width="1500"/>
</p>

<p align="center">
  <img src="readme_data/project_obs_2.png" alt="Observation Image" width="1500"/>
</p>

<p align="center">
  <img src="readme_data/project_obs_3.png" alt="Observation Image" width="1500"/>
</p>

<p align="center">
  <img src="readme_data/project_obs_4.png" alt="Observation Image" width="1500"/>
</p>

<p align="center">
  <img src="readme_data/project_obs_5.png" alt="Observation Image" width="1500"/>
</p>

<p align="center">
  <img src="readme_data/project_obs_6.png" alt="Observation Image" width="1500"/>
</p>

<p align="center">
  <img src="readme_data/project_obs_7.png" alt="Observation Image" width="1500"/>
</p>

<p align="center">
  <img src="readme_data/project_obs_8.png" alt="Observation Image" width="1500"/>
</p>

<p align="center">
  <img src="readme_data/project_obs_9.png" alt="Observation Image" width="1500"/>
</p>

<p align="center">
  <img src="readme_data/project_obs_10.png" alt="Observation Image" width="1500"/>
</p>

<p align="center">
  <img src="readme_data/project_obs_11.png" alt="Observation Image" width="1500"/>
</p> <br>

<!------ Result and Analysis ------>
<p align="center"><h2>💠 Results & Analysis </h2></p>
<p align='justify'>
▸ By employing a <strong><code>Binary Tree search algorithm</code></strong> for waypoint navigation, I achieved over 99% accuracy in my path tracking tests.

▸ The Binary Search Tree (BST) algorithm significantly enhances the efficiency of waypoint look-ahead, allowing for rapid searches and updates. This is crucial for autonomous navigation where high accuracy is essential.

▸ Binary Search Tree (BST) algorithm structured approach is ideal for handling densely packed or frequently updated waypoints, ensuring minimal delay in target point identification. Its application in the Pure Pursuit controller demonstrates exceptional performance, underlining its value in optimizing guidance for autonomous vehicles.
</p> <hr> <br> <br>

<!------ End Image ------>
<p align="center">
    <img src="readme_data/hk_quote.png" alt="HK Quote" width="1500"/>
</p>
