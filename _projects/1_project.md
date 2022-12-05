---
layout: page
title: Multi-Directional Drawing using TM5-900 Manipulator
description: Course project of Robotics
img: assets/img/drawn_snoopy.png
importance: 1
category: Course Projects
---

 We wanted to make a robot arm to draw a image on a plane with any angle. We first applied Canny edge detection algorithm to obtain image contours. Then we formulated a trajectory‑forming algorithm to decide the trajectories to draw an image given the contours. At last we tested our work using a Snoopy image. The TM5-900 manipulator successfully drew the image on an inclined plane.

 Here is our project report: [Report]({{ site.url }}/assets/pdf/ReportRobotics.pdf)

<div class="col-sm-12 text-center">
    
        {% include figure.html path="assets/img/drawn_snoopy.png" title="example image" class="img-fluid rounded z-depth-1" %}
    
</div>
<div class="caption">
    This is the Snoopy image drawing result.
</div>








