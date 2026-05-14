# Modal-Analysis-of-a-Rectangular-wing
This project performs finite element modal analysis of a simplified rectangular wing structure to identify its natural frequencies and mode shapes. For aeroelastic design, modal analysis is the foundation. Flutter speed depends directly on the natural frequency of the structure(wing) and how aerodynamic forces couple with each mode.
## Background
Every structure has natural frequencies and mode shapes, determined purely by its mass and stiffness distribution. For a wing, the first bending and first torsion modes are the most flutter criical because classical flutter arises from aerodynamic coupling between these two modes. In this project, these frequencies are identified for a cantilever aluminium wing using finite element analyisis.
## Material and Geometry
Wing Geometry: Rectangular planform, 1m span, 0.2m chord, 0.01m thickness.
Material: Aluminium alloy(E= 71GPa, v= 0.33, rho= 2770KG/m^3).
Boundary condition: Cantilever wing fixed at root face, free at tip. This is a representation of a wing rigidly attached to fuselage.
## Methodology
Wing Geometry was created in SpaceClaim and meshed with 3D solid elements, with an element size of 0.02m, in ANSYS Mechanical. Fixed support was applied to the root face. First six natural frequencies and mode shapes were extracted.
## Result
Mode 1: First Bending 8.32 Hz
Mode 2: First Torsion 52.06 Hz
Mode 3: Second Bending 80.67 Hz
Mode 4: Second Torsion 146.00 Hz
Mode 5: Third Bending 159.14 Hz
Mode 6: Combined Bending-Torsion 246.94 Hz
