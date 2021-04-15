# Problem statement
1. MLCC demand is increasing
2. MLCCs are exposed to more than 10 reliability tests including:
	1. Thermal shock
	2. **board flex (bending)**
	3. biased humidity tests
## Board flex test
Is used to evaluate the mechanical resistance to #cracking when MLCCs are subjected to #bending stress on the printed circuit board (PCB) that the MLCC is soldered on.
#bending can be happened when: 
- between manufacturing steps
- during operations under temperature variations

#cracking by #bending can cause:
- low DC resistance
- short circuit
- significant loss of #Capacitance which results in:
	- critical failure of a complete circuit

According to the reability standard, a change in the capacitance of MLCC should be 
*less than 12.5% under 2~3 mm board bending*
![[Pasted image 20210411220340.png]]

Thermal #ResidualStress are accumulated in the MLCC on cooling from the termination firing temperatures
Evenmore, during the soldering process, an additional thermal stress is superimposed

# Assumptions
The thick laminated active layer is reduced or a part of the active layers is simplified into an:
- equivalent
- homogeneous
- anisotropic
solid

# Parameters
$\sigma_{p,max}$ = maximum principal stress in the ceramic
=

# Material Properties
![[Pasted image 20210411220408.png]]
![[Pasted image 20210411221857.png]]
![[Pasted image 20210411221930.png]]

# Mathematical formula
![[Pasted image 20210412001032.png]]


Expected Results
=
![[Pasted image 20210411235532.png]]
![[Pasted image 20210412000903.png]]
![[Pasted image 20210412000924.png]]

can be referred to [[Finite element analysis]]



