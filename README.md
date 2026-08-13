This project compares several numerical interpolation techniques through an application to the Phillips Curve using Italian macroeconomic data. The objective is not to accurately model the Phillips Curve, but to evaluate the numerical properties of different interpolation algorithms.

The implemented methods include Lagrange interpolation, Newton interpolation, Neville's algorithm, local interpolation, quadratic splines and cubic splines.

The algorithms are compared in terms of computational efficiency, numerical stability and relative approximation error.

In terms of computational efficiency, Neville's algorithm proved to be the fastest interpolation method. Regarding numerical stability, Newton interpolation outperformed both Lagrange and Neville interpolation, exhibiting consistently lower relative errors. Among the spline-based methods, quadratic splines showed better stability than both cubic splines and local interpolation.

## Dataset
Annual unemployment and inflation rates for Italy (2013–2022).

Algorithms

Lagrange interpolation
Newton interpolation
Neville's algorithm
Local interpolation
Quadratic splines
Cubic splines
