---
layout: page
title: Obstacle Avoidance in Dense Environments using
MPC
description: "Course project of MEAM 5170: Control and Optimization with Applications in Robotics, Penn"
img: assets/img/MEAM_5170.png
importance: 1
category: Course Projects
---

This report investigates the impact of obstacle avoidance strategies on the performance of Model Predictive Control (MPC) in dense environments. Two methods, Local Model Predictive Contouring Control (LMPCC) and the Dynamic Window Approach (DWA), were analyzed. A novel improvement, Obstacle Window Filtering (OWF), was proposed to enhance LMPCC's efficiency and safety in cluttered settings.

The study reveals that while LMPCC effectively plans smooth trajectories and outperforms DWA in complex scenarios, its performance deteriorates as the number of obstacles increases due to computational bottlenecks. DWA, on the other hand, is computationally faster but fails in crowded environments where it cannot find feasible paths. OWF addresses LMPCC's limitations by selectively filtering distant obstacles from the optimization problem, significantly reducing computation time and improving safety metrics. For instance, OWF lowered the collision percentage by 44% in extreme cases with 40 obstacles, compared to standard LMPCC.

Simulations evaluated the algorithms' task time, collisions, collision percentage, collision speed, and computation time. While DWA showed promise in simple settings with fewer obstacles, it was less robust than LMPCC and OWF in dense scenarios. The results demonstrate that incorporating obstacle filtering enhances LMPCC's ability to navigate crowded environments safely and efficiently.

The findings highlight the trade-offs between computational efficiency and robustness in real-time obstacle avoidance. They also underscore the limitations of traditional MPC methods in scaling to dynamic, cluttered environments. This reinforces the need for integrating machine learning techniques into control frameworks to predict obstacle dynamics and enhance computational tractability. Future research could explore cooperative planning approaches and real-time adaptations to improve performance further.
 
 Here is our project report: [Report]({{ site.url }}/assets/pdf/MEAM_5170.pdf)


<div class="col-sm-12 text-center">
    
        {% include figure.html path="assets/img/MEAM_5170.png" title="example image" class="img-fluid rounded z-depth-1" %}
    
</div>
<div class="caption">
    This figure shows LMPCC generates a smooth trajectory to reach the goal while avoiding obstacles.
</div>








