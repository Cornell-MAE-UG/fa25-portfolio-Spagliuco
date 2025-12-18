---
layout: project
title: MAE 4272 Blade Design Project
description: Advanced CAD Project
technologies: [Autodesk Fusion]
image: /assets/images/windturbine.png
---
 For the MAE 4272 Blade project, I was asked to work with a team of 3 other students to design wind turbine blades for a small scale wind turbine. This design had several contraints, such as geometry, a chosen fixed angular velocity, and wind velocity defined by Weibull probability distribution. The reason for this project was to utilize fluids, fundamental design concepts, and teamwork into a singular project. The ultimate goal was to produce a blade with the highest power output possible. 

For the design process, a MATLAB script was made to iterate the blade geometry inorder to optimize power output and ensure structeral integrity.

**Inputs:**
- Blade geometry constraints  
  - Radius: **6 inches**  
  - Fixed angular velocity: **1200 RPM**
- Blade cross-section: **NACA 6412**
- Weibull wind speed distribution
- Material properties

**Process:**
- Blade Element Theory (BET) calculations informed by the **Betz limit**
- Lift force calculations used to determine **maximum blade stress**

**Output:**
- Optimized chord length
- Pitch distribution
- Twist distribution
- Maximum calculated stress: **239.52 kPa**

The final blade design is shown below:
<img src="{{ 'assets/images/blade1.png' | relative_url }}" alt="Blade Geometry" style="width:110%; display:block; margin:auto;">
<img src="{{ 'assets/images/blade2.png' | relative_url }}" alt="Blade Geometry" style="width:110%; display:block; margin:auto;">

***Testing summary:***
 To test the design of the blades, a wind tunnel was used to collect power curves at different wind speed controlled by the fan frequency. This was done by ramping a torque voltage input to the blade motor to zero, increasing the wind tunnel fan to a specific frequency, and then increasing the torque voltage by .2 and collecting data using the LabView at each point. 

This resulted in power curves:

<img src="{{ 'assets/images/powercurves.png' | relative_url }}" alt="Blade Geometry" style="width:110%; display:block; margin:auto;">

Which allowed for extrapolation at each wind speed to find the power output at the ideal RPM chosen, and compare with the therotical power output:

<img src="{{ 'assets/images/expirementalvstheoretical.png' | relative_url }}" alt="Blade Geometry" style="width:110%; display:block; margin:auto;">

I spefically was in charge of CADing the blades ensuring that they met the overall dimension requirments. I used AutoCAD to model the blades. 