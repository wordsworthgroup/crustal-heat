# crustal-heat
Numerics for the one-dimensional heat equation applied to a planet's crust

This repository provides a class for solving the one-dimensional heat equation with mixed boundary conditions, a temperature at the surface and a geothermal gradient at the bottom. It allows spatially variable thermal properties and time-varying boundary conditions. The class uses finite volumes and a time stepper from [libode](https://github.com/wordsworthgroup/libode). It also chooses its own time step to maximize efficiency. Latent heat can be enabled to simulate freezing and thawing of ground ice/water. Openmp and the class-based structure of this code make it good for running a large number of independent integrations. Simulating crustal heat transfer over wide ranges of initial conditions and/or physical parameters.

Documentation is here: [https://wordsworthgroup.github.io/crustal-heat/](https://wordsworthgroup.github.io/crustal-heat/)
