In order to run the program, it is only necessary to use the main.m file. 
The following functions and scripts developed for the sake of the project are included:
- main.m -> contains material inputs and initial conditions
- Flight_trajectory.m -> mounts the ODEs and solves the problem
- Heat_Flux_Sphere.m -> returns the heat flow rate
- Aerodynamics_Sphere.m -> returns the Cd
- coesamethod_alt.m -> returns atm conditions, based on built-in Matlab function
- c_Al.m -> returns Aluminum's specific heat
- Cp_air.m -> returns air's specific heat

Additional functions related to the atmosphere models are also included:

Matlab's COESA method:
- coesamethod.c -> Matlab's built-in function
- coesamethod.mexw64 -> 1976 COESA tables used by coesamethod.c
- CalcTemp.m

StandardAtmos William Gravel functions:
- StandardAtmos.m
- UniversalDefinitions.m
- MolecularWeightRatios.m
- GasSpecies.m
- CalcTemp.m
- CalcPressure.m
- CalcNumberDensity.m
- AtmosphericLayers.m
- AirComposition.m
