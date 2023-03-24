---
title: Metamorphic Testing in the context of Autonomous Drone Simulations
date: '2021-09-29'
type: book
weight: 50
---

## Overview

<div style="text-align: justify;">
  
Metamorphic testing has been applied in many domains and has proven to be effective for test case generation and fault detection. It is a software testing strategy that uses certain relations between input-output pairs of a program, referred to as metamorphic relations. In this paper, we provide an overview of metamorphic testing as well as an implementation in the autonomous systems domain. We cover the fundamental concepts of this testing technique in theory and implement it in a simulation with autonomous drones, where we also give some technical insight into the setup and usage of the implementation. We utilise the GNC API alongside our testing program in order to test obstacle detection and avoidance capabilities of autonomous drones in our simulation.

The technical environment consists of the Gazebo simulator, ArduPilot and the Robot Operating System. The GNC API implements an object avoidance strategy that is
based on the potential field method, where obstacles generate a repulsive potential and the robot is considered a particle. Various metamorphic relations are defined within this thesis and used for metamorphic testing in the simulation implementation. We identified several properties and some weak spots of both the implementation and the avoidance algorithm. The results indicate that this testing strategy shows great potential in the autonomous drones domain and should be recommended to developers in autonomous
systems and simulations.
</div>

### Keywords: 
  system-level testing, simulation, artificial intelligence, autonomous system, metamorphic testing, gazebo, ROS

- **Level**: Bachelor's
- **Type**: Thesis 
- **Status**: Completed since 05.11.2021
- **Student**: [Linus Eisele](https://www.researchgate.net/profile/Linus-Eisele-2)
- view: 4 


