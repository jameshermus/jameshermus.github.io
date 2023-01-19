---
layout: page
title: Manipulation Project
description: Term project for MIT course 6.843 - Robotic Manipulation taught by Russ Tedrake.
img: /assets/img/projects/work/manipulation/manipulation_2arm.png
importance: 2
category: work
---

<div class="row">
<a href="{{ 6.8323_FinalReport.pdf | prepend: 'assets/pdf/' | relative_url}}" target="_blank" rel="noopener noreferrer" class="float-right"><i class="fas fa-file-pdf"></i></a>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/projects/work/manipulation/manipulation_1arm.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/projects/work/manipulation/manipulation_2arm.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Abstract: Humans easily bimanually manipulate objects which may induce contact or coupled instability. The task of using a power drill is especially interesting as instability may arise in several ways. In this work we explore the task of power drilling with one and two Kuka Iiwa arms through simulation in drake. The task was accomplished by super imposing several controllers: an impedance to regulate gripper translation and rotation, a nullspace projected joint space impedance to resolve the redundancy, a feedforward torque to compensate the mass of the drill after it was picked up, and a torque to compensate for gravity. Impedances were chosen to be human-like. Minimum jerk trajectories smoothly moved the nominal position of the gripper controller between waypoints. The second Iiwa, when used, provided a stabilizing impedance in all directions except for downwards to not interfere with the task. Using this approach, both the unimanual and bimanual systems were able to move into stable contact with the ground and generate a downward force on the drill of 32 Newtons.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
<iframe width="560" height="315" src="https://www.youtube.com/embed/djhSE1Nj9u8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
</div>

<br>

<html>
  <head>
    <title>Title of the document</title>
  </head>
  <body>
    <iframe src="/assets/pdf/6.8323_FinalReport.pdf" width="100%" height="500px">
    </iframe>
  </body>
</html>

