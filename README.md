# Numerical Methods for Differential Equations
The aim of this project is to showcase computational methods for solving both ordinary and partial differential equations. 
This includes the construction, application and analysis of basic computational algorithms for approximate solutions on 
a computer of initial value, boundary value and eigenvalue problems for ordinary differential equations, and for partial 
differential equations in one space and one time dimension.

<p align="center">
  <img src="https://github.com/AliBakly/Numerical-Methods-for-Differential-Equations/assets/21970392/98aa73d7-c612-481f-bd07-f9d16e770418" width="600">
</p>

## Runge Kutta Methods
We construct our own ODE solver, based on an explicit Runge-Kutta method with embedded error estimator. The error estimator is used to adjust the time step along the integration, so that the error estimate is kept close to a prescribed accuracy tolerance.

Furthermore, we focus on understanding the distinction between stiff and nonstiff problems, and why stiff problems require implicit methods with unbounded stability regions. We will study two nonlinear oscillatory systems, the nonstiff Lotka-Volterra population dynamics problem and the van der Pol equation, which may be stiff or nonstiff depending on problem parameters. We work both with our own solver, and a professionally implemented stiff ODE solver.

## Boundary Value Problems (BVPs)
In this notebook we present the required theory and the methodology of constructing solvers for two-point boundary value problems as well as Sturm-Liouville eigenvalue problems. Basic finite difference methods are introduced by a thorough implementation. However, we do not consider making the solver adaptive and neither do we consider nonlinear problems as they present additional difficulties. We present a few applications of the theory, such as quantum mechanics.

## Partial Differential Equations (PDEs)
 In this project, we will work with parabolic and hyperbolic partial differential equations, and combine elementary techniques from $2p$ -BVPs with time-stepping methods from IVPs. The goal is to gain experience with the method of lines and stability constraints of Courant-Friedrichs-Lewy (CFL) type on the time-step $\Delta t$.

