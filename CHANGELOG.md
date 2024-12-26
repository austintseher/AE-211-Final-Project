# CHANGELOG

All documented changes of "satellite_plotter" program

## Satellite Plotter 

**Author:** Austin Seher

### [1.0.0] - 2024-04-29
#### Added
- Ability to name orbit and output 2D, 3D and orbit as '.png' and 'x,y,z' coordinates to a '.mat' file
- Titles, axis titles and labels for all graphs
#### Removed
- Outputting orbital coordinates to a '.txt' log file
#### Fixed
- Math mapping orbit to 2D plot was incorrect
	- Now plots according to a Mercator projection
- Rotational matrix for offset from prime meridian is now correct
### [0.4.0] - 2024-04-26
#### Added
- Orbit coordinates are now output to a '.txt' log file
- More implementation of 2D orbit plot
### [0.3.0] - 2024-04-25

#### Added
- Added rough implementation of 2D graph of Earth's Surface
- Added ability to add inclination angle
#### Changed
- Calculate orbit is now done in 3 dimensions instead of 2
- makeearth function is now called plotearth 

### [0.2.0] - 2024-04-23

#### Added
- Added ability to rotate orbit in degrees from Earth's prime meridian
- Separate function (calculate_orbit) to calcuate orbital parameters
#### Changed
- Earth is temporarily rendered at a lower resolution to increase performance during testing
### [0.1.0] - 2024-04-22

#### Added
- Added an image to Earth so it is not a uniform sphere
- Added basic orbit plotting ability
	- Can only currently plot based on Apogee and Perigee, more implementation planned in future