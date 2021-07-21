Steps in a CFD analysis:
0 = Physical problem to mathematical model (PDEs)
1 = Mesh teh CAD(pre-processing)
2 = Define analysis type
3 = Specify fluid properties & boundary conditions
4 = Select numerical schemes
-  Solvers and interpolation schemes for solution of equation system
5 = Post-processing of results
- Pressure loss/gain
- Vorticity
- Forces

In short:
real world --> PDEs --> Algebraic equations --> Code --> Generated data
# Cradle
## scFLOW
1. Modifying and importing CAD geometry data
2. New function
3. Simple preprocessor operation (useful assisting functions)
4. Polyhedral mesher
5. Moving element (discontinuous mesh)
6. Free surface
7. Particle tracking
8. Radiation (emission)
9. Diffusion
10. Compressibility (compressible,incompressible)
11. Cavitation
12. scMonitor
13. Solver
14. Postprocessor

#CourantNumber is used to represent how far across the cell the fluid is moving in given time step
#CourantNumber is a ratio between fluid distance with cell distance
![[Pasted image 20210715203230.png]]
