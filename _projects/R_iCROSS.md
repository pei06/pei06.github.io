---
layout: page
title: iCROSS
description: Design and Evaluation of the infant Cardiac Robotic Surgical System (iCROSS)
img: assets/img/iCROSS.jpg
importance: 1
category: Research Projects
---
The <span class="font-weight-bold">Design and Evaluation of the Infant Cardiac Robotic Surgical System (iCROSS)</span> was the primary research project I was involved in during my undergraduate years. This research focuses on developing a dual-arm surgical robot system to assist infant PDA closure through teleoperation, including mechatronics, system integration, and mechanical and software design. I was responsible for the software of this robotic system which mainly included the following tasks: designing and implementing a software structure that manages joystick-based human-robot interaction and detects self-collision of the surgical robot.


By developing a force rendering algorithm and post-processing the joystick readings using Unity, I successfully overlapped the workspaces for teleoperation and provided haptic feedback. I implemented a rapid collision detection algorithm that could run at 60 Hz using LabVIEW regarding collision avoidance. The algorithm is a modified version of oriented bounding boxes (OBB), which differs from the original version by a more detailed bounding mechanism using different geometries and constructing several conditional statements to increase calculation speed. These promising results led to our publication in IROS 2022.


Publication Link: [IROS 2022](https://ieeexplore.ieee.org/document/9981503?fbclid=IwAR33YrXJFXWVlRh2ZS0LvqCIAdVxeTQPoBSbUfLo0q9ULANQs3EhmmIph8A)

Publication PDF: [PDF](../../assets/pdf/Design-and-Evaluation-of-the-infant-Cardiac-Robotic-Surgical-System-(iCROSS).pdf)

Demo video at: [Demo](https://www.youtube.com/watch?v=RACPwt9ZMvE)


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/iCROSS.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The iCROSS. (1)The infant heart model. (2)Two instruments operating simultaneously. (3)The 6-DoF robot manipulator. (4)Camera. (5)The tool driver for specific surgical instruments. (6)The Real-Time Target.
</div>