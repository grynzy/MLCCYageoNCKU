*1st task to modeling the binder removal in a ceramic system is to understand all of the working components of the phenomenon*

Main processes are:
1. Thermal reaction of the binder
2. Mass transport of the volatile products from the reaction

## Polymers
- very large molecular structure
- chain-like with repeating units
- if it is organic compound, it has a backbone chain of carbon atoms
- Low densities
- Ductile and pliable

Binder burnout is used to remove the polymer from the porous green body, which is accomplished by thermal degradation
	- Need to understand the thermal degradation process
	
Polymer does not degrade into a volatile form in a single  step

Polymer --> solid1 --> gas1			Solid1 --> solid2  --> gas2

==Challenge==
The degradation of the polymer into an intermediate solid and a gas occurs at a lower temperature than the degradation of the intermediate solid to a gas.
The weight loss profile of this reaction would have at least two regions of rapid weight loss since the gases are produced at different temperatures.
	- This can be caused by different reaction rate
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

## COMSOL Multiphysics
Was used to solve equation (17)
![[Pasted image 20210419153429.png]]

==**Physics of the Reaction**==
=
# 1. Determining the Reaction Kinetics

# 2. Creating a Numerical Model for Pressure

# 3. Multiple Volatile Species Created During Thermal Degradation

==**Computational Model**==
=
# 1. Reaction Scenarios Modeled in COMSOL

==**Discussion and Conclusion**==
=
1. A model has been made to track the *internal pressure* of a green body as it is subjected to a *heating sequence for the purpose of binder removal*
2. 
