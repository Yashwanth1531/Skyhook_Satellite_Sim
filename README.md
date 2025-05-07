# Modeling and simulating the dyanamics of a Skyhook

This project was part of Spacecraft Dynamics and Control course. The repo contains the report and all the codes used for the project.

<video controls src="Small_oscillation_sat_1m.mp4" title="Oscillation of dumbbell satellite with no spin intially
"></video>

## Contents
- **Dumbell_sat_sim.py**
```
+ This file contains all the function definitions for the simulations. When the file is run it plots the state variable time evolution. 

+ By enabling the save flags inside the file it also saves all the relavent data in .npz file and the plots as .pdf file.

```
- **Skyhook_vizualization.py**
```
This file reads the time series data from the saved .npz file and shows a 3D vizualization of the satellite in orbit. The vizualization will not be upto scale.
```
- **Project_report.pdf**
```
This file contains all the necessary information including the derivation for the simulation.
```