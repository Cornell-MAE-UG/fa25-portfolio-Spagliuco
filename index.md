---
layout: default
title: <Your Name>
---

## About Me


![Profile Picture](/assets/images/profile-pic.jpg){: class="profile-image"}
 
My name is {{ site.name }}, and I am a class of Spring 2026 Mechanical Engineer. POOP

MAE 4272 BLADE PROJECT: 

Project overview: For the MAE 4272 Blade project, I was asked to work with a team of 3 other students to design wind turbine blades for a small scale wind turbine. This design had several contraints, such as geometry, a chosen fixed angular velocity, and wind velocity defined by Weibull probability distribution. The reason for this project was to utilize
Fluids, fundamnetal design concepts, and teamwork into a singular project. The ultimate goal was to produce a blade with the highest power output possible. 

Design process: 
For the design process, a MATLAB script was made to iterate the blade geometry inoder to optimize power output and ensure structeral integrity. 

Input: Blade geometry restrictions (Radius: 6 inchs,  fixed angular velocity: 1200RPM), Blade Cross section (NACA 6412), Weibull wind speed, Materail Propeties 
Process: Blade Element Therory calculations based on Betz limit, Calculated lift Force to find maximum blade stress
Output: Chord length, Pitch, Twist, and a max stress of 239.52 kPa.

![Profile Picture]({{ "assets/images/blade1.png" | relative_url }}){: class="profile-image"}

Testing summary: To test the design of the blades, a wind tunnel was used to collect power curves at different wind speed controlled by the fan frequency. This was done by ramping a torque voltage input to the blade motor to zero, increasing the wind tunnel fan to a specific frequency, and then increasing the torque voltage by .2 and collecting data using the LabView at each point. 

This resulted in power curves:
![Profile Picture]({{ "assets/images/powercurves.png" | relative_url }}){: class="profile-image"}

Which allowed for extrapolation at each wind speed to find the power output at the ideal RPM chosen, and compare with the therotical power output:

![Profile Picture]({{ "assets/images/expirementalvstheoretical.png" | relative_url }}){: class="profile-image"}


Your contribution: Briefly describe what you worked on
I spefically was in charge of CADing the blades ensuring that they met the overall dimension requirments. I used AutoCAD to model the blades. 

Figures: Plots, CAD image, and photos 

This is not a full technical report. Aim for 2–4 concise paragraphs plus 1–3 informative graphics.


Take a look at <a href="{{ "/projects/" | relative_url }}">my projects</a> and <a href="{{ "/cv/" | relative_url }}">CV</a>.
