---
layout: page
title: Multi-Directional Drawing
description: Course project of Robotics, NTU
img: assets/img/drawn_snoopy.png
importance: 2
category: Course Projects
---

 This project aims to control a robot arm to draw on an arbitrary plane. The following tasks were crucial to achieving the goal: image processing, trajectory formulation, and visual pose estimation. We applied the Canny Edge Detection algorithm to obtain image contours. Then we developed a trajectory‑forming algorithm to decide the trajectories given the contours. By solving the Perspective-n-Points problem, we can estimate the 3D pose using 2D images on the plane. We tested our work using a Snoopy image, and the TM5-900 manipulator successfully drew the image on an inclined plane.

 
 Here is our project report: [Report]({{ site.url }}/assets/pdf/ReportRobotics.pdf)

Demo video at: [Demo](https://www.youtube.com/watch?v=3nGta4v2xv8&t=10s)

 If you are interested in our code, this is our Github repo: [Repo](https://github.com/pei06/multidirectioinal_painter)

<div class="col-sm-12 text-center">
    
        {% include figure.html path="assets/img/drawn_snoopy.png" title="example image" class="img-fluid rounded z-depth-1" %}
    
</div>
<div class="caption">
    This is the Snoopy image drawing result.
</div>








