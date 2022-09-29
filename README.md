# Analysis on Heat Equation Stability based on the Von-Neumann Stability Analysis using Forward/Backward Euler methods
The code which implements the Forward Euler method for the famous heat equation.
The Algorithm first calculates the initial profile f(x) for a certain point on spatial
domain as j∆x. Then, the temperature function will be updated as the time steps evolve,
by using the centeral difference method for approximsting the u_xx .
If we implement the Von Neumann stability analysis to this method, the amplification
factor is has to be between 0 and 0.5. 
For different values for alpha the stability and unstability of the numerical solution has been shown. 
