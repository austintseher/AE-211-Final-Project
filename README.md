# README
## Overview
- This program (sattilite_plotter) plots the orbit of a satellite around Earth based on its Apogee, Perigee, Rotational offset from the prime meridian and inclination relative to the equator
	- It doesn't account for physical characteristics of Earth (i.e., gravity, rotation, mass, ect.), only geometric ones
- It outputs a 3D model of the orbit and a 2D map of the orbit over Earth's surface
### Current Version [1.0.0]

The project is currently active
Last change: 2024-04-30

#### Author: Austin Seher

## Install Guide
1. Install the **image analyzer** add-on for MATLAB
2. Download "Seher_Austin_Final.zip"
3. Extract zip file to its own folder
4. Open "main_script.mlx" in MATLAB
5. Open the extracted folder as the working directory in MATLAB
6. Select the extracted zip folder from step 2 as the working directory in MATLAB
## Usage Guide
1. Run the "main.mlx script"
2. Input variables for:
	- Apogee (km above Earth's surface)
	- Perigee (km above Earth's surface)
	- Offset angle (degrees from prime meridian)
	- Inclination angle (degrees from equator)
## Known Bugs
- Occasional freeze when plotting orbit
	- To fix rerun program