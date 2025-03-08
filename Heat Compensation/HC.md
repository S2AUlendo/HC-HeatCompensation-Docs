---
layout: default
title: Ulendo Heat Compensation
description: "An overview of the Ulendo HC Desktop Application"
has_children: true
nav_order: 2
---

# Ulendo HC Desktop Overview
Ulendo HC Desktop is a powerful desktop application designed to optimize CLI files for Laser Powder Bed Fusion (LPBF) 3D printing. The tool provides an intuitive user interface to visualize and analyze CLI models before and after optimization, ensuring users can see the impact of the adjustments in real-time.

The software supports various LPBF printer parameters and machine profiles, making it adaptable to different printer models and configurations. By intelligently reordering the hatch patterns within each layer of the CLI file, the HC algorithm optimizes for heat distribution across the build surface. This optimization minimizes the risk of part deformation caused by uneven heating, leading to higher-quality prints with improved mechanical properties.

Whether you're working with standard or custom machine settings, the HC desktop application offers flexibility and precision in optimizing your print jobs. The application is ideal for manufacturers, researchers, and engineers looking to enhance their LPBF processes and achieve more reliable, consistent results from their LPBF machines.

### HC algorithm parameters
The software can be used with the default parameters or additional parameters can be set or passed into the software. 
In order of the usage the available parameters to configure the module, include:

    1.  Conductivity [W/mK]
    2.  Density [kg/m^3]
    3.  Heat Capacity [J/kgK]
    4.  Scanning speed [mm/s]
    5.  Convection coefficient [W/m^2K]        
    6.  Laser power [W]


![Optimization History.](https://s2aulendo.github.io/HC-HeatCompensation-Docs/assets/images/ulendo-hc-app-flow.png)

> {: .note }
  The input CLI file should contain both polylines and hatchlines before being run in the HC application.