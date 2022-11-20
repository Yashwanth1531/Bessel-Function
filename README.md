# Bessel-Function
- This repository contains codes for plotting and visualizing Bessel functions and its applications -


Several second order ODEs of the form 𝒚
′′ + 𝒑(𝒙)𝒚
′ + 𝒒(𝒙)𝒚 = 𝒓(𝒙) are of 
practical importance have Power series solution 𝑦(𝑥) = ∑ (𝑥 − 𝑥0)
∞ 𝑛
𝑛=0
if 
coefficients p(x), q(x) and r(x) are functions instead of constant coefficients. 
Further, if they must have valid Taylor series expansion about point 𝑥0, means they 
must be continuously differentiable about that point i.e. they are analytical at that 
point.
If the coefficients p(x), q(x), r(x) are not analytical at point 𝑥0 but if we still require 
a power series solution at that point, in order to exploit the larger radius of 
convergence, we use Frobenius method. Frobenius methods masks the point of 
singularity, thereby creating feasible solution at which the power series method 
fails. Such points are called regular singular points.
Consider an example ODE:

𝑦
′′ +
2
𝑥
𝑦
′ +
1
𝑥
2
𝑦 = 0
