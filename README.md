# 2D-Room-Mapping

This project demonstrates a low-cost, portable system for mapping a 2D representation of a room using an ultrasonic sensor connected to an Arduino. The system calculates and visualizes coordinates based on distance measurements and angular positions. The generated map can assist in applications such as robotics navigation, small-scale surveying, and spatial visualization.

Target Beneficiary:-

The primary beneficiaries of this project include:

* Robotics enthusiasts.

* Students and educators in STEM disciplines.

* Developers working on indoor mapping or navigation systems.

The primary objective of this project is to design and implement a portable, low-cost system capable of generating a 2D map of a room using basic sensor measurements. This system will:

* Capture distance data using an HC-SR04 ultrasonic sensor at varying angles.

* Process the data to calculate Cartesian coordinates using trigonometric algorithms.

* Dynamically visualize the results in real-time using Python-based plotting libraries.

* Provide a simple, scalable solution that can be adapted for various use cases, such as robotics navigation, indoor mapping for education, and preliminary spatial analysis.

Methodology

5.1 Data Structures and Algorithms Used

* Data Structures: Lists to store distance and coordinate data.

* Algorithms: Trigonometric calculations for coordinate transformation:

ox=d⋅cos⁡(θ)x = d \cdot \cos(\theta)x=d⋅cos(θ)

oy=d⋅sin⁡(θ)y = d \cdot \sin(\theta)y=d⋅sin(θ)

5.2 Tech Stack

Programming Languages:

* Python (for visualization)
* C++ (Arduino sketch)
  
Libraries Used:

* matplotlib for real-time plotting.

* pyserial for communication between Arduino and Python.

5.3 System Requirements

* Operating System: Linux-based system (e.g., Linux Mint or Ubuntu 22.04).

* Software: Python 3.x, Arduino IDE.




