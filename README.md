# Ant-Based satellite cyber security research
This is a NetLogo3D simulation for modeling cyber security networks in space systems, currently being developed at the
University of North Dakota as a part of the OpenOrbiter small satellite development program.

The simulation pulls data from the two spreadsheets to create satellites and ground stations. The satellite data is the most accurate and robust that I could find.
The ground station data is simply test data for now, and will most likely be generated in the future.

To run after cloning this repository, simply download NetLogo3D from [here](https://ccl.northwestern.edu/netlogo/), navigate to the install directory, and then launch NetLogo3D.
Find and open `simulation.nlogo3d`, and the simulation should be ready to go. 

Pressing "setup" and then "go" will start satellite and ground station movement. 
Agents in this simulation orbit with accurate (scaled) period and take Earth's rotation into account in their latitude and longitude calculation.
Satellites and ground stations with the same frequency will attempt to connect with one another.

The current goal of this simulation is to allow for research on the concept of using individual "ants" on many different satellites to detect abnormalities
in signals, commands, etc.
