---
layout: default
title: Results
description: "A Result overview of the Ulendo HC Desktop Application."
parent: Ulendo HC Desktop
nav_order: 4
---

# Ulendo HC Results

The results section provides a side-by-side comparison of the pre-optimized and post-optimized hatch sequences for each layer of the CLI file. This allows users to visualize how the sequence has been reordered to promote more even heat distribution, reducing the likelihood of deformities in printed parts.

## Understanding the results
The optimized sequence shown in the results demonstrates how the sequence of the fragments within a layer patterns have been reordered to minimize localized heating and ensure uniform heat distribution across the layer. Research has shown that this optimization significantly enhances the overall print quality and reduces deformation risks, providing a reliable foundation for high-precision manufacturing.


## Sequence Visualization  
By default, the app displays only the optimized sequence of the part fragments. For performance reasons, only the bounding box of the regions, and the order in which they are scanned.

### Heat Dissipation Visualization  
The app uses a fading color scheme to represent the relative timing of the scanned hatches in a layer.  
Newly scanned hatches are displayed in **red**, gradually fading through **purple**, and finally to **blue** to indicate that the heat has dissipated.  
**Note**: This is a conceptual representation of the heat dissipation and not an accurate heat map. Future updates will include a more realistic heat distribution model.

## Side by Side Comparison
Users can toggle, the **"Show Original"** option to view the original sequence, in a side by side view with the optimized version. This allows users to see the differences between the original sequence and the new - optimized sequence. 

## Interactive Slider  
Use the **layer slider** to navigate through individual layers of the model.  
To view the exact laser path, users can optionally, view the actual laser scan path via the **hatch slider**.

## Playback Feature  
User can access the **play button** to show an automated animation the fragment sequences for a layer. This can used to visualize the order in which hatches are scanned during the printing process.



