# Research Objective
Use computational methods to predict the #kinetic of #binder removal as a function of:
- composition
- particle size
- pore size and turtuosity
- temperature
- body size and shape

# Dependent variables
- Composition
- temperature
- pore pressure
as function of:
- time
- position within the body
- heating sequence

# Outcome
Prediction of optimum heating sequences that minimize processing time and energy input while avoiding harmful high internal pressures and temperatures

TGA ( #thermogravimetric analysis) of binders will be used to measure kinetics parameters that are inputs for the computational model

# Software
COMSOL Multiphysics

# Important findings
1. The removal of the binder occurs as the binder is heated to a temperature taht allows liquid diffusion or gas-phase diffusion.
2. As the melting temperature of the binder is reached and it begins to vaporize, the volatile products tranpsort through the porous media out of the body
3. Challange in binder burnout:
	1. Need to be removed quickly
	2. The binder must navigate the porous media in order to escape the body
	3. If volatile species are produced faster than the green body's porous pathways which allow for mass transport, internal pressure will buildup
		1. Failure at critical pressure
4. Therefore, the heating sequences for binder removal must be slow enough to stay below the critical pressure threshold but fast enough to justify the use of binders
5. The interaction between binder degradation and mass transport through the porous body is difficult to predict

#Assumptions
1. Conduction is the only mode of heat transfer in the green body (heat of reaction and convective heat transfer are negligible)
2. Thermal diffusivity does not vary with temperature
3. Binder burnout decomposition kinetics are determined on a per-species basis, but the products are all gases
4. #Darcy's law is used to describe the gas flow of decomposition products out of the body
	1. Assumed when the pore size is large relative to the mean free path of the gas-phase species, used here because this is the case of slower transport and therefore larger internal pressure being the rate limiting factor