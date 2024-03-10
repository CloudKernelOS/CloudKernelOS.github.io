---
layout: page
title: SoNS
permalink: /SoNS/
---


## SoNS Architecture

The general principles of [Self-organizing Nervous Systems(SoNS)](https://arxiv.org/abs/2401.13103) is our starting point for thinking about the architecture of robot swarms. The concept of SoNS addresses what we see as the critical dichotomy in thinking about an architecture for swarm robotics systems: the trade-off between centralized control and decentralized autonomy. 

### Traditional Approaches:

**Centralized Systems**: These systems have a single point of control, which can be limiting due to potential points of failure and scalability challenges.

**Decentralized Systems:** These are fully self-organized but can be challenging to design analytically.

### The SoNS Approach:

The Self-organizing Nervous System (SoNS) is a novel architecture that bridges this gap between centralized and decentralized systems.

It enables robots to autonomously establish, maintain, and reconfigure dynamic multi-level system architectures.

Imagine a robot swarm consisting of n independent robots. With SoNS:

* It can transform into a single n-robot SoNS.
* Then, it can further divide into several independent smaller SoNSs.
* Each SoNS uses a temporary and dynamic hierarchy.
* SoNS allows for locally centralized coordination without sacrificing scalability, flexibility, or fault tolerance.
* Sensing, actuation, and decision-making become more efficient within this framework.

### Applications and Advancements of SoNS

SoNS has been demonstrated in various robot missions, including binary decision-making and search-and-rescue scenarios.

Real heterogeneous aerial-ground robot swarms have been used for these missions.

The capabilities of SoNS significantly advance the state of the art in swarm robotics.

### Scalability and Fault Tolerance

SoNS has been tested with swarms of up to 250 robots in a physics-based simulator.

It exhibits robustness and fault tolerance in both simulation and real-world scenarios.

### Summary

The Self-organizing Nervous System empowers robot swarms to dynamically adapt their architecture, combining the best of both centralized and decentralized approaches. 
