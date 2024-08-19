# Stepped-Euler-Bernoulli-Beam
Analytical solution of the Euler-Bernoulli bending beam for a non-constant bending stiffness using singularity functions. 
The solution is available for a beam with two supports `oneFieldBeam.mlx` and a beam with three supports `twoFieldBeam.mlx`. 
The boundary conditions of supports can be chosen between fixed and pinned end.

The live script `examples.mlx` contains examples for the functions `oneFieldBeam.mlx` and `twoFieldBeam.mlx`.

The live functions `oneFieldBeam.mlx` and `twoFieldBeam.mlx` calculates the displacement, rotation, curvature and bending moment for a single-span and a two-span beam with changing bending stiffness. 

The live functions uses singularity functions to implement the changing bending stiffness in the beam.
Also the load and support forces are modelled with singularity functions.
See reference for detailed explanation.


# Reference
Static, Vibration Analysis and Sensitivity Analysis of Stepped Beams Using Singularity Functions by Peng Cheng, Carla Davila and Gene Hou.


# Acknowledgement
This work is part of the ZEBBRA project, which is funded by the Federal Ministry of Education and Research.
