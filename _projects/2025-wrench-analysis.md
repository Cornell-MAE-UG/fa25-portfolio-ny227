---
layout: project
title: Wrench Analysis
description: Class project 
technologies: [ANSYS Workbench, MATLAB]
image: /assets/images/wrench.png
---


For a class, we were asked to create a torque wrench that satisfies the following conditions: safety factor of Xo = 4 for yield or brittle failure, safety factor of XK = 2 for crack growth from an assumed crack of depth 0.04 inches, fatigue stress safety factor of XS = 1.5, and material must be a steel, aluminum or titanium alloy.
<br>
Worked With: Anish Dhawan

<br>

![CAD Model of Wrench](/fa25-portfolio-ny227/assets/images/wrench_dimensions.png)

<br>
The material we ended up modeling the wrench after  was AISI 4150 steel. It is a medium-carbon, chromium-molybdenum low-alloy steel. It’s a widely used alloy in structural, mechanical, and automotive components due to its balance of strength, toughness, hardenability, and wear resistance. 4150 in the normalized (this is often used as a pre-heat treatment before quenching, tempering, and a final condition process when moderate strength and toughness are desire) condition is heated above the austenitizing temperature and air-cooled, improving toughness, machinability, and a refined, uniform ferrite-pearlite microstructure.
<br>
<br>
The wrench was applied with a 600 in-lbf moment on its end, with its drive being set with a boundary condition such that its displacement is zero.

![Wrench Moment](/fa25-portfolio-ny227/assets/images/wrench_moment.png)
![Drive Boundary Conditions](/fa25-portfolio-ny227/assets/images/drive_displacement.png)

<br>
<br>
Normal Strain Countour Map from FEM Analysis

![Strain Contour](/fa25-portfolio-ny227/assets/images/wrench-5.png)
<br>
Maximum Principle Stress Contour Map from FEM Analysis
![Principle Stress Contour](/fa25-portfolio-ny227/assets/images/wrench-6.png)
<br>
Summarized Results of FEM Analysis
![summary1](/fa25-portfolio-ny227/assets/images/wrench-7.png)
![summary2](/fa25-portfolio-ny227/assets/images/wrench-8.png)
![summary3](/fa25-portfolio-ny227/assets/images/wrench-9.png)
<br>
From the FEM: Maximum Normal Stress at Gauge = 98.917 psi, Load Point Deflection = 0.43315 in, and Strain at the Strain Gauge Location = 1011 microstrain. These values are consistent with our calculations:
![handcalc](/fa25-portfolio-ny227/assets/images/wrench-10.png)
<br>
<br>
Torque Wrench Sensitivity = 1011 microstrain x 1000 = 1.011 mV/V
<br>
<br>
Strain Gauge Selected:
![straingauge](/fa25-portfolio-ny227/assets/images/wrench-11.png)