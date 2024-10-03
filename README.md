# Overview
This repository contains a simple framework to study the time taken by the Minimum Weight Perfect Matching (MWPM) algorithm for varying sizes of photonic systems. The framework has inbuilt modules for creating a fusion network (with 6-qubit resource states). This fusion network is then leveraged to make inputs for the MWPM algorithm.
The notebook also evaluates the statistical distribution of hamming weights for a configurable fusion failure rate (currently set to 40%).

# How to play with the notebook?
Feel free to try out different system sizes (by varying the variables num_x, num_y and num_z which indicate the number of unit cells in the X, Y and Z direction respectively. The error rate as well as the number of times the simulation runs can be configured by modifying the "error_rate" and "nsims" variables respectively.

# What can I get from the notebook?
The notebook does an extensive simulation to get an accurate representation of the hamming weight (the number of 1's in the collected parity) and the time taken by the MWPM algorithm for this system.
Lastly we generate plots for the above for easy visualization.
