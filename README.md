# Self-Driving-Cars-Specialization
There are 4 courses in this specialization. Course content for each course is as follows:
* **Introduction to Self-Driving Cars**: This course will introduce you to the terminology, design considerations and safety assessment of self-driving cars.  By the end of this course, you will be able to:
  - Understand commonly used hardware used for self-driving cars
  - Identify the main components of the self-driving software stack
  - Program vehicle modelling and control
  - Analyze the safety frameworks and current industry practices for vehicle development

  Final project goals:
  - ___Develop control code to navigate a self-driving car around a racetrack in the [CARLA](http://carla.org/) simulation environment___
  - ___Construct longitudinal and lateral dynamic models for a vehicle and create controllers that regulate speed and path tracking performance using Python___

* **State Estimation and Localization for Self-Driving Cars**: This course will introduce you to the different sensors and how we can use them for state estimation and localization in a self-driving car. By the end of this course, you will be able to:
  - Understand the key methods for parameter and state estimation used for autonomous driving, such as the method of least-squares
  - Develop a model for typical vehicle localization sensors, including GPS and IMUs
  - Apply extended and unscented Kalman Filters to a vehicle state estimation problem
  - Understand LIDAR scan matching and the Iterative Closest Point algorithm
  - Apply these tools to fuse multiple sensor streams into a single state estimate for a self-driving car

  Final project goal: ___Implement the Error-State Extended Kalaman Filter (ES-EKF) to localize a vehicle using data from the CARLA simulator___


* **Visual Perception for Self-Driving Cars**: This course will introduce you to the main perception tasks in autonomous driving, static and dynamic object detection, and will survey common computer vision methods for robotic perception.  By the end of this course, you will be able to:
  - Work with the pinhole camera model, perform intrinsic and extrinsic camera calibration
  - Detect, describe and match image features and design your own convolutional neural networks
  - Apply these methods to visual odometry, object detection and tracking
  - Apply semantic segmentation for drivable surface estimation

  Final project goals: ___Develop algorithms that identify bounding boxes for objects in the scene, and define the boundaries of the drivable surface___

* **Motion Planning for Self-Driving Cars**: This course will introduce you to the main planning tasks in autonomous driving, including mission planning, behavior planning and local planning.   By the end of this course, you will be able to:
  - Find the shortest path over a graph or road network using Dijkstra's and the A* algorithm
  - Use finite state machines to select safe behaviors to execute, and design optimal, smooth paths and velocity profiles to navigate safely around obstacles while obeying traffic laws
  - Build occupancy grid maps of static elements in the environment and learn how to use them for efficient collision checking.

  Final project goal: ___Implement a hierarchical motion planner to navigate through a sequence of scenarios in the CARLA simulator, including avoiding a vehicle parked in your lane, following a lead vehicle and safely navigating an intersection___

## What you will learn
- Understand the detailed architecture and components of a self-driving car software stack
- Implement methods for static and dynamic object detection, localization and mapping, behaviour and maneuver planning, and vehicle control
- Use realistic vehicle physics, complete sensor suite: camera, LIDAR, GPS/INS, wheel odometry, depth map, semantic segmentation, object bounding boxes
- Demonstrate skills in CARLA and build programs with Python
