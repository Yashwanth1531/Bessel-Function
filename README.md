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

In above example problem p(𝑥) and q(𝑥) are undefined at 𝑥 = 0 but we can still 
apply frobenius method if 𝑥0 is regular singular point of ODE. The solution 
according to Frobenius is by 𝑦(𝑥) = ∑ 𝑎𝑛𝑥
𝑛+𝑟 = 𝑥
𝑟
(𝑎0 + 𝑎1𝑥 + ⋯ )
∞
𝑛=0
𝑥0 is the regular singular point of 𝑦
′′ + 𝑝(𝑥)𝑦
′ + 𝑞(𝑥)𝑦 = 0 if (𝑥 − 𝑥0
)𝑝(𝑥) and 
(𝑥 − 𝑥0
)
2𝑞(𝑥) exist and has valid Taylor expansion about 𝑥0. The exponent r (may 
be real or complex) number should be chosen such that 𝑎0 ≠ 0.
Now, there exists a class of 2
nd order, linear ODEs with variable coefficients of the 
form: 
𝑥
2𝑦
′′ + 𝑥𝑦
′ + (𝑥
2 − 𝑚2
)𝑦 = 0
The Bessel function of the first kind of mth order is given by:

J_m(x) = Sum[Divide[Power[\(40)-1\(41),L],Power[2,2l+m]*L!*\(40)m+L\(41)!],{L,0,∞}]*Power[x,2L+m]

𝑌_𝑚(𝑥) =
𝐽_𝑚(𝑥) cos 𝜋𝑚 − 𝐽_−𝑚(𝑥)
sin 𝜋m





𝛹(𝑟 − 𝑡) = ∑ ak exp(−λk
2
αt) 𝐽0
(λkr).
∞
𝑘=1
