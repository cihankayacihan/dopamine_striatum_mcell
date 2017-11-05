# An MCell model of DA reuptake in the striatum

The mdl files contains information related to geometry, molecules, reactions, surface regions, release patterns, outputs and simulation parameters. 

## Geometry

The geometry file is constructed in Blender using CellBlender. The exported geometry is in mesh format which includes the coordinates of the corners of the triangular meshes and their connections. In addition, selected surface areas are also identified using triangle numbers. 

## Molecules 

The molecules file contains the name and diffusion constants of the molecule types in the simulations. Four different types of DAT molecules are identified to represent the different states of DAT molecules. DA molecules are defined as volume molecules.

## Reactions 

The reaction file contains the reactants and products for all possible change in the system. The forward and backward reaction rates are also defined. Some reactions are named to be used in output section. 

## Surface regions

The surface classes file defines a class which lets DA molecules to pass through. The exteriors of the release spheres are modified to DA_trans surface class. 

## Release Patterns

The release patterns file contains the release times and the shapes of DA release. It is possible to modify the length or shape of pulse input. 

## Outputs

The reaction outputs file records the total number of DA molecules in simulation box and spheres with variable radii around release sites. Also, it holds the total number of DAT in each state. The visualization output file contains the information about the frequency of frame recording and what molecules need to be tracked. 

## Simulation parameters

Initialization file containts several important parameters related to surface density of molecules and interaction distances. 

## Main 

Main file contains the information related to molecule placement, simulation length and information related to partitions of the simulation box. 

Overall, the system could be simulated with MCell 3.3 or 3.4. MCell is a C-based code and it does not need any additional software to work. Different version of MCell software is available in https://mcell.org.


