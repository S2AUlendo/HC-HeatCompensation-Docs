---
layout: default
title: Ulendo Heat Compensation
description: "An overview of the Ulendo HC Desktop Application"
has_children: true
nav_order: 1
---

# Ulendo HC (Heat Compensation)
The Ulendo HC Desktop Application derives from the compensation-based technologies for
additive manufacturing developed by Ulendo Technologies, Inc. The underlying algorithm in
Ulendo HC significantly improves the performance of a Laser Power Bed Fusion (LPBF) printer
by optimizing the path of the laser to reduce part deformation and stress. The technology is
available in this desktop application and also as a plugin to Additive Manufacturing software
platforms such as Dyndrite LPBF.

Parts produced by metal LPBF printers are prone to residual stress, deformation, cracks and
other quality defects due to uneven temperature distribution during the printing process. To
address this issue, Ulendo has developed an algorithm that optimizes the laser scan sequence
resulting in a 50% reduction in mean deformation and 88% reduction in residual stress. Instead
of using a trial-and-error approach to selecting a heuristic scan sequence (e.g., stripe,
chessboard, spiral), Ulendo HC automatically develops a custom scan sequence based on the
geometry of the part and the metal being used. Using a physics model-based and optimization-
driven approach, Ulendo HC achieves higher part quality than using heuristics.

For the Ulendo HC Desktop Application, a user selects a CLI<sup>1</sup> file for the part to be printed as
well as the metal to be used for the part and then selects PROCESS to create an optimized CLI
file to be used in the LPBF printing process. The user can examine a layer-by-layer
representation of the temperature gradients in the part.

### Ulendo HC Desktop Overview
Ulendo HC Desktop is a powerful desktop application designed to optimize CLI<sup>1</sup> files for Laser
Powder Bed Fusion (LPBF) 3D printing. The tool provides an intuitive user interface to visualize
and analyze CLI models before and after optimization, ensuring users can see the impact of the
adjustments in real-time.

The software supports various LPBF printer parameters and machine profiles, making it
adaptable to different printer models and configurations. By intelligently reordering the hatch
patterns within each layer of the CLI<sup>1</sup> file, the HC algorithm optimizes for heat distribution across
the build surface. This optimization minimizes the risk of part deformation caused by uneven
heating, leading to higher-quality prints with improved mechanical properties.

### HC algorithm parameters
The software can be used with the default parameters or additional parameters can be set/
passed into the software. The available parameters to configure the module include:

  1.  Conductivity [W/mK]
  2.  Density [kg/m<sup>3</sup>]
  3.  Heat Capacity [J/kgK]
  4.  Scanning speed [mm/s]
  5.  Convection coefficient [W/m<sup>2</sup>K]        
  6.  Laser power [W]


![HC Flow.](https://s2aulendo.github.io/HC-HeatCompensation-Docs/assets/images/ulendo-hc-app-flow.png)

> {: .note }
  The input CLI<sup>1</sup> file should contain both polylines and hatchlines before being run in the HC application.

  <sup>1</sup>The application can be enhanced to accommodate additional file types.