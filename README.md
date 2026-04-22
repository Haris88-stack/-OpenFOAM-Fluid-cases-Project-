# -OpenFOAM-Flow-around-cube-Project-
This repository contains OpenFOAM simulations of fluid flow around a cube. The geometry and mesh were generated using Gmsh, and the simulations investigate flow behavior such as velocity distribution, pressure fields, and wake formation.

The project includes all necessary case setup files, including mesh definitions, boundary and initial conditions, and solver configurations, allowing for straightforward reproduction and analysis of the results.

Each case follows the standard OpenFOAM directory structure:

- `0/` : Initial and boundary field files
- `constant/` : Material properties and mesh files
- `system/` : Control dictionaries and solver settings
- `scripts/` : Post-processing scripts
- `geometry.geo` : Geometry defined using Gmsh
- `geometry.msh` : Mesh generated using Gmsh

Download the full project folder here: [Flow-around-cube.zip](Flow-around-cube.zip)
