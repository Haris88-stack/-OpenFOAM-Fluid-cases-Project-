# -OpenFOAM-Fluid-cases-Project-
This repository contains OpenFOAM simulations of fluid flow around simple benchmark geometries. The geometries and meshes were generated using Gmsh, and the simulations investigate flow behavior such as velocity distribution, pressure fields, and wake formation.

The project includes all necessary case setup files, including mesh definitions, boundary and initial conditions, and solver configurations, allowing for straightforward reproduction and analysis of the results.

This repository contains OpenFOAM cases for simulating flow around different geometries using meshes generated with Gmsh.

# Cases

- **Flow Around a Cube**
Simulation of fluid flow around a cube, focusing on velocity and pressure distribution, as well as flow separation and recirculation zones.

- **Flow Around a Cylinder**
Simulation of flow around a cylinder, commonly used as a benchmark case to study wake dynamics, vortex shedding, and pressure distribution.

# Folder Structure

Each case follows the standard OpenFOAM directory structure:

- `0/` : Initial and boundary field files
- `constant/` : Material properties and mesh files
- `system/` : Control dictionaries and solver settings
- `scripts/` : Post-processing scripts
- `geometry.geo` : Geometry defined using Gmsh
- `geometry.msh` : Mesh generated using Gmsh

Download the full project folder here: [Fluid-cases.zip](Fluid-cases.zip)
