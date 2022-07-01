# Numerical Analysis of Parallel Plate Capacitor
 
 This simulation intends to numerically determine the capacitance of a parallel plate capacitor on a non-ideal regime, i.e. considering border effects.
 
 The Successive Over-relaxation (SOR) method was used to solve the Laplace Equation for the electric potential, with constant potential at both plates (with opposite signs). The gradient was taken numerically to get the electric potential at the vicinities of the capacitor, and the charge per unit lenght was found using Gauss's Law.

Convergence was studied for the SOR method with several values of the ω parameter.

All results found are available at the [notebook](https://github.com/caiomarxm/realCapacitorPotential/blob/main/RealCapacitorAnalysis.ipynb).
