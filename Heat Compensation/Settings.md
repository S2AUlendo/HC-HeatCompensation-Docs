---  
layout: default  
title: Settings Menu  
description: "Configuring performance and optimization settings in the Ulendo HC app."  
parent: Ulendo Heat Compensation  
nav_order: 5
---  

# Ulendo HC Settings Menu  

The **Settings Menu** allows users to configure performance and optimization parameters to balance speed, accuracy, and resource usage. Users can access the settings by navigating to **File > Settings** in the window menu.

By default, optimized files are stored in Program Files/UlendoHCTool/output. Use the **File > Change Output** Directory option to change the location of these optimized files.

## Processing Modes  
Users can choose from four processing modes that control how many CPU threads the app will allocate to optimization tasks. These modes impact the computation time and overall performance, allowing users to customize their experience based on system capabilities:

- **Reserved** - Uses minimal CPU resources, preserving system performance for other tasks.
- **Balanced** - Allocates a moderate number of CPU threads for optimization while keeping system responsiveness.
- **Conservative** - Uses more CPU threads than Balanced but avoids full utilization.
- **High Performance** - Utilizes all available CPU cores for maximum optimization speed.

These modes impact the computation time and overall performance, allowing users to customize their experience based on system capabilities.

## Advanced Settings  
### Hardware Acceleration  
**Note:** Hardware acceleration is currently **not functional** in version **0.3.1**. This setting is disabled by default and does not impact performance in the current release.

## Layer Downscaling Feature  
The **Layer Downscaling Feature** is enabled by default and improves performance by simplifying complex layers before optimization:

- If a layer exceeds a set number of features (adjustable by the user), it is **downsampled** to reduce complexity.
- The optimization algorithm is applied to the simplified layer.
- After optimization, the layer is **upscaled** back to its original resolution.

This feature significantly reduces computation time and memory usage, though it may slightly affect accuracy. Users can adjust the threshold for downscaling based on their preference.

## Saving Settings  
Once adjustments are made, click **Save Settings** to apply changes. The settings will persist across sessions.

---

For additional guidance, visit the [Troubleshooting](#) section or contact support at **info@ulendo.io**.

