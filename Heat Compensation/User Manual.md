---
layout: default
title: User Manual
description: "How to use Ulendo HC Desktop"
parent: Ulendo Heat Compensation
nav_order: 3
---

# User Manual
The BLUE Help dropdown provides in-app assistance for the user.

## 1. Upload a File  
* Click the **"Choose File"** button to upload a file for processing that has been generated using a slicer.
* NOTE: Currently the desktop application accepts CLI files, but other file types can be accommodated by contacting Ulendo.   
![Material Selection.](https://s2aulendo.github.io/HC-HeatCompensation-Docs/assets/images/select-input.png)

## 2. Select Material and Printer  
* Users can create a custom material or printer OR modify an existing material or printer.
* Select the material that best matches the powder to be used during the printing process.
* Users can manually edit the parameters to match the information provided by the powder manufacturer.
* Specify the laser scanning speed and laser power corresponding to the machine and the material to be used. If different speeds and power settings are used for different parts of the build, enter the configuration that best represents the average speed.
  
![Material Selection.](https://s2aulendo.github.io/HC-HeatCompensation-Docs/assets/images/material-selections-2.png)

* Users can manually edit the parameters to match the information provided by the powder manufacturer.  
![Material Parameters.](https://s2aulendo.github.io/HC-HeatCompensation-Docs/assets/images/show-material-params.png)

* Select the laser scanning speed, and laser power for the material to be used. If different speeds and power settings are used for different parts of the build, enter the configuration that best represents the average speed.  
![Machine Parameters.](https://s2aulendo.github.io/HC-HeatCompensation-Docs/assets/images/hc-machines-params.png)

## 3. View Before Optimization  
Click the **"View"** button to inspect the original file before processing.

![View Screen.](https://s2aulendo.github.io/HC-HeatCompensation-Docs/assets/images/hc-app-viewscreen.png)

## 4. Optimize the File  
Click the **"Optimize"** button to reorder the hatch patterns for even heat distribution.

![Optimizing File.](https://s2aulendo.github.io/HC-HeatCompensation-Docs/assets/images/hc-processing.png)

## 5. View Processing History  
The **"History"** section lists any files that have been successfully optimized with the Ulendo HC application. To view the results of the optimization, click a file name to quickly access it.

![Optimization History.](https://s2aulendo.github.io/HC-HeatCompensation-Docs/assets/images/opt-history.png)

## 6. Explore the Results Tabs  
Once optimization is complete, users can analyze results using two tabs:

### Sequence Visualizer  
This tab displays the optimized hatch sequence. Users can examine the **order of scanning**, ensuring improved heat distribution across layers. The visualization helps identify how hatch patterns were adjusted to reduce localized heating.

### Temperature Uniformity  
This tab provides a **heat deviation graph**, which visualizes temperature distribution across layers. The graph indicates areas where heat concentration may lead to deformation and shows how optimization improves temperature uniformity.

## 7. Compare Results  
Users can toggle the **"Show Original"** option to view a **side-by-side comparison** of the original and optimized sequences.

![Analysis Screen.](https://s2aulendo.github.io/HC-HeatCompensation-Docs/assets/images/analysis-comparison.png)

Use the **slider** to navigate through layers and examine the hatch patterns.

## 8. Playback Hatch Sequence  
* Use the **playback controls** to animate the hatch sequence and visualize the printing process layer by layer.
* Use the icons at the top of the results pane to export a png file of the results, zoom in/out, etc.


