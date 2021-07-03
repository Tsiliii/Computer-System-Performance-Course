# Computer-System-Performance-Course
Network simulation for Computer System Performance Course NTUA (10th Semester)

# Table of Contents
1. Python notebook with simulation code and results visualization.
2. Project Report (Greek)

## Workspace
The work was implemented using python notebook on google colab workspace. No higher function libraries were used, everything is vanilla.

## Network
The designed system is made up of a CPU handling (in charge of handling all arrivals) and a disk. Jobs of two categories are arriving as Poisson processes in the system. The execution times in the CPU and the disk are exponentially distributed and the queueing system is non trivial.

## Simulation results
Using the regenerative method of simulation we calculate the average response time per job for every category and the average CPU and Disk utilization (with 95% confidence intervals).
