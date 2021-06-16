# Numerical Methods

A course on numerical methods covering:

* Introductory numerical analysis (interpolation, quadrature, etc)
* Numerical linear algebra (solving linear systems, methods for solving nonlinear systems)
* Numerical solution of ODEs (including time-stepping methods suitable for unsteady PDEs)
* Numerical solution of PDEs (approaches to discretise the spatial dimensions: the finite difference, volume and element methods - FDM/FVM/FEM)

## Learning outcomes

On successful completion of this module, students will be able to:

1. Describe and implement numerical methods to solve typical (algebraic/ differential, linear/non-linear) equations, including ordinary differential equations (ODEs), partial differential equations (PDEs) and linear/non-linear systems.
2. Contrast the fundamental properties of different numerical algorithms: complexity, stability, accuracy, consistency, convergence, and boundedness.
3. Critique the key numerical approaches for the solution of problems from continuum mechanics.
4. Apply knowledge of spatial and temporal discretisation methods and their properties.

## Description of content

This module will operate at the interface of the Modelling Dynamical Processes module (ACSE-2) introducing key physics and mathematical underpinning, i.e. the continuous world, and the Modern Programming Methods module (ACSE-1) for how to interact with computers.  It will also provide knowledge of key algorithms that will be used in Applying Computational Science (ACSE-4).

This module will introduce the key concepts and algorithms required to represent the continuous world on discrete computers.  Introductory fundamental concepts that are common across all numerical methods will be introduced:  stability, accuracy, consistency, convergence, boundedness, conservation, etc.

Algorithms from numerical linear algebra and for the numerical solution of ODEs (implicit and explicit) and PDEs will be introduced. These will be motivated by the physical problems introduced in ACSE-2, and looking ahead to the requirements of future modules (ACSE-7 and ACSE-8 in particular) as well as the major projects (module ACSE-9).

## Reading list

The notes provided are self-contained, but if you would like suggestions for additional reading try the following:

* Practical Numerical Methods with Python, Lorena Barba, Ian Hawke and Bernard Knaepen \[A MOOC with IPython Notebooks available at: [https://github.com/numerical-mooc/numerical-mooc/wiki](https://github.com/numerical-mooc/numerical-mooc/wiki)\]
* Numerical Methods in Engineering with Python 3, 3rd Edition, Jaan Kiusalaas
* Fundamentals of Engineering Numerical Analysis, 2nd Edition, Parviz Moin
* A First Course in the Numerical Analysis of Differential Equations, 2nd Edition, Arieh Iserles
* Numerical Linear Algebra, Lloyd N. Trefethen, David Bau III
* Finite Difference Methods for Ordinary and Partial Differential Equations: Steady-State and Time-dependent Problems, Randall LeVeque
* Finite Volume Methods for Hyperbolic Problems, Randall LeVeque
* Finite Elements and Fast Iterative Solvers: with Applications in Incompressible Fluid Dynamics, 2nd Edition,  Howard Elman, David Silvester and Andy Wathen
* Computational Methods for Fluid Dynamics, 3rd Edition, Joel Ferziger and Milovan Peric

## Lecture plan

The plan is to lecture Monday - Thursday, with Friday being a consolidation day.

As with ACSE-2 I will lecture in the morning with GTAs available to answer questions in the afternoons, as well as morning and afternoon on Mondays.


1. Interpolation and curve-fitting

2. Numerical integration (or quadrature)

3. Numerical linear solvers (e.g. Gaussian elimination)

4. Nonlinear solvers (e.g. Newton's method)

5. ODEs 1 (simple time-stepping schemes; stability

6. ODEs 2 (more advanced time-steppers - Runge-Kutta and linear multistep methods)

7. Numerical differentiation and BVPs (finite differences; shooting method)

8. PDEs 1 (1D problems; advection and diffusion; stability)

9. PDEs 2 (2D problems; incompressible computational fluid dynamics (CFD))

10. FVM (finite volume methods; hyperbolic PDEs and compressible CFD)

11. FEM 1 (finite element methods; weak forms, assembly and implementation)

12. FEM 2 (finite element methods; 2D problems and computational fluid dynamics)

## Assessment

A single piece of assessed coursework will be released towards the end of week 3, with a submission deadline of 8th January 2021.
