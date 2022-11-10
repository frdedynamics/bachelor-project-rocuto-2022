# Bachelor Project on RoCutO - a Robotic Grass Cutter for Orchards
 Bachelor Project (AUT 2022) in the Robotic Grass Cutter for Orchards (RoCutO) project.

## Project Background
 This Bacheor project is connected to the RoCutO project running at HVL Robotics 2022-2023. The production of fruits and berries has a long tradition in Western Norway and remains until today an important economic sector. However, many producers struggle to stay competitive in face of high labour costs. RoCutO has the goal to develop an autonomous robot grass cutter for orchards to relieve producers from manual groundcover management. The groundcover management in orchards plays a key role in modern fruit and berry production. The excessive growing of weeds under fruit trees and berry bushes is undesirable since under-crop vegetation competes for water and nutrients which reduces the crop yield and plant growth. Also, vegetation between the orchard-rows should be kept to a minimum to provide access for workers and machines and to reduce vole habitat. Opposed to other agricultural mowing, grass cutting in orchards is a more involved task. The confined space in orchards and their location in often steep terrain impedes the use of tractors and conventional heavy machinery. Mowing robots for household use, on the other hand, do not have sufficient cutting, mobility, and navigation capacities, and the necessary robustness for agricultural use. RoCutO will fill this gap by integrating enough cutting capacity into a small yet robust 4x4 mobile robotic platform, equipped with cameras and sensor systems for intelligent navigation in a rugged and dynamic environment.
 Such a robot system has immediate use in fruit and berry production in Western Norway, especially in the regions of Sogn and Hardanger. RoCutO has great potential to benefit regional agriculture, reduce herbicide use and contribute to a green economy.

 Examples of the conditions and vegetation in orchards in Lærdal:

 <img src="project description\laerdal_orchard_1.jpg" width=25% height=25%> <img src="project description\laerdal_orchard_2.jpg" width=25% height=25%> <img src="project description\laerdal_orchard_3.jpg" width=25% height=25%>


## Problem
 This bachelor project supports work package 1 *Selection and implementation of grass cutting mechanism and actuation* in the RoCutO project. This work package is concerned with analyzing, evaluating and selecting a cutting mechanism that is suitable for grass cutting in orchards. Cutting capability, safety, weight and size and the integration on a small mobile robot (Husky) have to be considered.
 The cutting mechanism must be actuated such that the robot can easily cut grass in narrow gaps (between trees, around polytunnel scaffolding, etc.) and avoid obstacles (e.g. rocks) without maneuvering the whole mobile robot platform. It has to be considered how many degrees of freedom are necessary, what kinematic structure is suitable and which types of actuators are suitable.

 **Tasks:**
 - Evaluating different cutting mechanism (circular, linear, with blades or with wires, etc.)
 - Selecting an off-the-shelf actuator for the cutting mechanism 
 - Designing the kinematic structure, and simulating the robot with the actuated cutting tool in Gazebo
 - Designing and implementing the power supply, the control electronics, and the data interface with ROS/Husky
 - Considering sensors for the cutting assembly
 - Building a simple prototype module that fits on the Husky robot
 - Demonstrating basic powered cutting and open-loop actuation in the field

 Available 4x4 mobile robot platform "Husky" from Clearpath robotics that could be equipped with the cutting assembly:

 <img src="project description\husky.jpg" width=25% height=25%>

 This project is best suited for group of 2-3 students.
 The focus of the Bachelor project could be adjusted according to preferences of the group.

## Contact and Supervision
[Daniel Schäle](dasc@hvl.no)

[Martin Stølen](Martin.Fodstad.Stolen@hvl.no)
