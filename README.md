# Autonomous-Vehicles
This repository includes the programming assignments and projects for the 4 course Self Driving Cars Specialization by University of Toronto on Coursera.

This Specialization gives you a comprehensive understanding of state-of-the-art engineering practices used in the self-driving car industry.You'll get to interact with real data sets from an autonomous vehicle (AV)―all through hands-on projects using the open source simulator CARLA.

Throughout your courses, you’ll hear from industry experts who work at companies like Oxbotica and Zoox as they share insights about autonomous technology and how that is powering job growth within the field.

You’ll learn from a highly realistic driving environment that features 3D pedestrian modelling and environmental conditions. 
When you complete the Specialization successfully, you’ll be able to build your own self-driving software stack and be ready to apply for jobs in the autonomous vehicle industry.

# 1.Introduction to Self Driving Cars.

This course will introduce you to the terminology, design considerations and safety assessment of self-driving cars.  By the end of this course, you will be able to: 
- Understand commonly used hardware used for self-driving cars
- Identify the main components of the self-driving software stack
- Program vehicle modelling and control  
- Analyze the safety frameworks and current industry practices for vehicle development

The final course project was the development of a control code to navigate a self-driving car around a racetrack in the CARLA simulation environment.Construction of longitudinal and lateral dynamic models for a vehicle and creation of controllers that regulate speed and path tracking performance using Python. 

# 2.State Estimation and Localization of Self Driving Cars.

This course will introduce you to the different sensors and how we can use them for state estimation and localization in a self-driving car. By the end of this course, you will be able to:
- Understand the key methods for parameter and state estimation used for autonomous driving, such as the method of least-squares
- Develop a model for typical vehicle localization sensors, including GPS and IMUs
- Apply extended and unscented Kalman Filters to a vehicle state estimation problem
- Understand LIDAR scan matching and the Iterative Closest Point algorithm 
- Apply these tools to fuse multiple sensor streams into a single state estimate for a self-driving car 

The final course project was the implementation of the Error-State Extended Kalman Filter (ES-EKF) to localize a vehicle using data from the CARLA simulator.

# 3.Visual Perception for Self Driving Cars.

This course will introduce you to the main perception tasks in autonomous driving, static and dynamic object detection, and will survey common computer vision methods for robotic perception.  By the end of this course, you will be able to work with the pinhole camera model, perform intrinsic and extrinsic camera calibration, detect, describe and match image features and design your own convolutional neural networks.  You'll apply these methods to visual odometry, object detection and tracking, and semantic segmentation for drivable surface estimation. These techniques represent the main building blocks of the perception system for self-driving cars.

For the final project in this course, you will develop algorithms that identify bounding boxes for objects in the scene, and define the boundaries of the drivable surface.  You'll work with synthetic and real image data, and evaluate your performance on a realistic dataset.

# 4.Motion Planning for Self Driving Cars.

This course will introduce you to the main planning tasks in autonomous driving, including mission planning, behavior planning and local planning.   By the end of this course, you will be able to find the shortest path over a graph or road network using Dijkstra's and the A* algorithm, use finite state machines to select safe behaviors to execute, and design optimal, smooth paths and velocity profiles to navigate safely around obstacles while obeying traffic laws.  You'll also build occupancy grid maps of static elements in the environment and learn how to use them for efficient collision checking. This course will give you the ability to construct a full self-driving planning solution, to take you from home to work while behaving like a typical driving and keeping the vehicle safe at all times.

For the final project in this course, you will implement a hierarchical motion planner to navigate through a sequence of scenarios in the CARLA simulator, including avoiding a vehicle parked in your lane, following a lead vehicle and safely navigating an intersection.  You'll face real-world randomness and need to work to ensure your solution is robust to changes in the environment.
