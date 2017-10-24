# About
This repository contains optimal complexity spectrally-accurate Poisson solvers on the rectangle, cylinder, solid sphere, and cube. The code accompanies the paper:

* [1] Dan Fortunato and Alex Townsend, *Fast Poisson solvers for spectral methods*, submitted, 2017.

# Getting started
To use the MATLAB code, first run `code/setup.m`. The Poisson solvers are:

* `poisson_rectangle.m`
* `poisson_cylinder.m`
* `poisson_solid_sphere.m`
* `poisson_cube.m`

Examples can be found in the `code/tests` directory. All figures in the paper can be generated by running `makeFigures.m`.
