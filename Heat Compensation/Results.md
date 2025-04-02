---
layout: default
title: Results
description: "A result overview of the Ulendo HC Desktop Application."
parent: Ulendo Heat Compensation
nav_order: 4
---

# Ulendo HC Optimization Results

## Sequence Visualizer

The results section provides a side-by-side comparison of the pre-optimized and post-optimized hatch sequences for each layer of the file. This allows users to visualize how the sequence has been reordered to promote more even heat distribution, reducing the likelihood of deformities in printed parts.

### Understanding the Results
The optimized sequence shown in the results demonstrates how fragment patterns within a layer have been reordered to minimize localized heating and ensure uniform heat distribution across the layer. Research has shown that this optimization significantly enhances overall print quality, reduces deformation risks and improves part consistency, making it ideal for high-precision manufacturing.

### Sequence Visualization  
By default, the application displays only the optimized sequence of the part fragments. For performance reasons, only the bounding boxes of the regions and their scan order are shown. At the top of the chart, users can find a table displaying the material and machine parameters selected for optimization.

The application uses a fading color scheme to represent the relative timing of the scanned hatches in a layer:  
- **Red** represents the most recently scanned hatches.  
- **Purple** represents intermediate cooling stages.  
- **Blue** represents fully cooled areas where heat has dissipated.  

**Note**: This is a conceptual representation of heat dissipation and not an exact thermal simulation. Future updates may include a more accurate heat distribution model.

### Side-by-Side Comparison
Users can toggle the **"Show Original"** option to view the original sequence alongside the optimized version. This allows for a direct comparison of how the optimization has altered the scan order to improve heat distribution.

### Interactive Slider  
Users can interact with the **layer slider** to compare thermal deviation improvements across different layers of the print.
To examine the exact laser path, users can enable the **hatch slider** to view the precise scan sequence.

### Playback Feature  
Users can access the **play button** to animate the hatch sequence for a selected layer. This visualization helps in understanding the printing order and how the optimization modifies the process.

## Thermal Deviation Analysis  
The **Thermal Deviation Over Time** graph provides insight into the heat uniformity of a print.  

- The **Y-axis** represents **thermal deviation**, with lower values indicating better heat distribution.  
- The **X-axis** represents **time**, showing how deviation evolves throughout the layer’s scan sequence.  
- **Blue (Original Sequence)** shows the deviation of the standard, unoptimized hatch pattern.  
- **Red (Optimized Sequence)** shows the deviation after applying Ulendo HC’s algorithm.  

A slower rate of deviation increase in the optimized sequence indicates improved heat uniformity, reducing warping and defects. The **Thermal Uniformity Grade** provides a quick assessment of the improvement, where a higher grade signifies better uniformity.  


---
