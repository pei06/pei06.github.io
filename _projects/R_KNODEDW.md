---
layout: page
title: KNODE-DW MPC
description: Flying Quadrotors in Tight Formations using Learning-based Model Predictive Control
img: assets/img/KNODEDW.jpg
importance: 0
category: Research Projects
---
I tackled the challenge of enabling quadrotors to fly in tight formations and navigate in the presence of complex downwash airflows. To accomplish this, I combined first-principle physics models with neural ODEs to accurately model the dynamics of quadrotor downwash. While MPC can be employed to achieve exceptional control performance, it requires a precise model of the system dynamics. As such, I developed a learning-based MPC framework — KNODE-DW MPC —by integrating the hybrid physics and neural ODE model with MPC. 

We obtained groundbreaking results with this framework such as a
40% performance improvement in trajectory tracking compared to nominal MPC in both simulations and physical experiments. I successfully flew two Crazyflie quadrotors in a stacked formation with only 12 cm of vertical separation—the first demonstration of its kind. This work resulted in a submission to ICRA 2025 where I am a co-first author.


Publication Link: [Submitted to ICRA 2025](https://arxiv.org/abs/2410.09727)

Publication PDF: [PDF](../../assets/pdf/KNODEDW.pdf)

Demo video at: [Demo](https://www.youtube.com/watch?v=Hv-0JiVoJGo)


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/KNODEDW.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    KNODE-DW MPC: Top: A composite photo depicting two
Crazyflie (CF) quadrotors flying in lemniscate trajectories, under a
stacked formation with a commanded separation of 2 body lengths.
This is achieved with our proposed framework. The frames used to
create this photo are extracted from a video taken during a physical
experiment. Bottom: Schematic of our framework.
</div>