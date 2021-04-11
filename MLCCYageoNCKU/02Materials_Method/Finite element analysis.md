# [[huang2015]]

# What to be investigated
- Mechanism of stress development in MLCCs under board flex tests
- Thermal residual stresses caused by the soldering process
- Flexural stresses resulting from bending tests

# What to be included
- active region
- termination region
- solder materials

# What to be discussed
Effects of four design parameters:
- metal inner electrodes
- lateral margin widths
- nickel termination thickness
- solder wicking height
On how to diminish the peak tensile stress during the board flex test

Stress at which MLCC cracks is dependent on:
- #MaterialProperty of the constituent components
	- Dielectric ceramics
	- Metal inner electrodes
	- Solders
	- Termination terminals
- #Geometry of the components
	- Solder fillets
	- widhts of the housing 
	- lateral margins
	- thickness of the electrode and dielectric materials
- #ResidualStress within the MLCC during manufacturing and soldering
- Macro #defect within the ceramic materials

Internal #ResidualStress state develops during:
- manufacturing
- termination firing
- soldering processes
Owing to:
thermal contraction behavior of each of the different materials present

#Geometry wise:
increase capacitor layer, decrease ceramic/electrode layers thickness

### Stresses in MLCCs can be simulated through the [[Finite element analysis]]

# Materials and Method
## Materials
### BaTiO3-based dielectric ceramics
#### Dimensions
- Electronics Industry Association(EIA) X7R0805
- 1850 x 1150 x 550 $\mu m$

### Metal inner electrodes
#### Dimensions
- 7 layers of nickel with thickness of 2 $\mu m$
- thickness of the dielectric ceramic layers is 14 $\mu m$
- lateral margin		= 300 $\mu m$
- housing margin	= 300 $\mu m$
- cover margin		   = 194 $\mu m$

### Termination structure
Consist of layer of (and thickness of):
- #copper 25 $\mu m$
- #nickel 6 $\mu m$
- #tin 6 $\mu m$
![[Pasted image 20210411132152.png]]
![[Pasted image 20210411135147.png]]
### Method
#Taguchi_L9_Method is adopted to:
1. analyze the effects of the aforementioned four design parameters 
2. determine the optimal design parameters necessary to minimize the peak tensile stress in the dielectric ceramics

# Assumptions
- Deformation behavior of the dielectric and the board is assumed to be elastic
- The plastic deformatoni of the metals is described by a bilinear kinematic hardening law (see: [[franken2004finite]])

# Expected results
![[Pasted image 20210411222922.png]]




