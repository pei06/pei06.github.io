---
layout: page
title: Qt-Ethercat Software System
description: A Qt UI for controlling devices through Ethercat
img:
importance: 2
category: Research Projects
---

Embedding other programming languages, such as C++, into LabVIEW is inconvenient. This disadvantage prevents us from effectively testing and evaluating algorithms and data structures' efficiency. Therefore a new software system that can control robots possessing the following functions is crucial: an operator interface coded with C++, a real-time operating system, and Ethercat communication with robots. After experimenting with various configurations, I found a feasible structure combining Qt, Linuxcnc, and Etherlab that fulfills the project's demands. With this software system, we can quickly implement and test algorithms that require more complicated data structures, such as classes, trees, and graphs.


Demo video of controlling a Maxon motor: [Motor](https://youtube.com/shorts/i1i4ws3Q7CE)


Demo video of sensor reading from a Force/Torque sensor: [F/T Sensor](https://www.youtube.com/watch?v=ZHXNW38Nkps)


