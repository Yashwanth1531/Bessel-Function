# Bessel-Function
- This repository contains codes for plotting and visualizing Bessel functions and its applications -


Several second order ODEs of the form 𝒚
′′ + 𝒑(𝒙)𝒚
′ + 𝒒(𝒙)𝒚 = 𝒓(𝒙) are of 
practical importance have Power series solution ![image](https://user-images.githubusercontent.com/111849605/202916187-f7610de8-73a3-4251-8c33-2c582ec94679.png)

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

![image](https://user-images.githubusercontent.com/111849605/202916235-19bd8b34-11c7-4508-bdc7-e51ad1c52776.png)


In above example problem p(𝑥) and q(𝑥) are undefined at 𝑥 = 0 but we can still 
apply frobenius method if 𝑥0 is regular singular point of ODE. The solution 
according to Frobenius is by 
![image](https://user-images.githubusercontent.com/111849605/202916298-fed44276-fd8a-4628-80e6-78eed9504fda.png)

𝑥0 is the regular singular point of 
![image](https://user-images.githubusercontent.com/111849605/202916359-913395b2-a100-4ddd-8b36-559d7a04bbfa.png)


if (𝑥 − 𝑥0
)𝑝(𝑥) and 
(𝑥 − 𝑥0
)
2𝑞(𝑥) exist and has valid Taylor expansion about 𝑥0. The exponent r (may 
be real or complex) number should be chosen such that 𝑎0 ≠ 0.
Now, there exists a class of 2
nd order, linear ODEs with variable coefficients of the 
form: 

![image](https://user-images.githubusercontent.com/111849605/202916399-86961cf9-8819-434b-9efe-39b80d110b2e.png)


The Bessel function of the first kind of mth order is given by:

J_m(x) = 
![image](https://user-images.githubusercontent.com/111849605/202916125-974ac718-c023-4ff6-a9f2-b47e2b9ed031.png)



![image](https://user-images.githubusercontent.com/111849605/202916433-51aa81fe-0508-4330-8598-be8d5326d4b0.png)

The behaviour of the Bessel functions of first kind 𝐽𝑚 of order ‘m’ are shown 
below:

![image](https://user-images.githubusercontent.com/111849605/202916473-6bd3e3f8-fbee-48f9-8d73-7e38f1ef11a9.png)

The behaviour of the Bessel functions of second kind 𝑌𝑚 of order ‘m’ are shown 
below:

![image](https://user-images.githubusercontent.com/111849605/202916498-5cf8a8ae-9a1b-4253-b5e2-7cfa3b497c5d.png)

A general solution of Bessel’s function for the Bessel ODE is given by 
𝑦(𝑥) = 𝐶1𝐽_𝑚 + 𝐶2𝑌_m

APPLICATION 1: CYLINDER WITH ENERGY 
GENERATION

A long solid cylinder of radius ro is initially at uniform temperature Ti. Electricity 
is suddenly passed through the cylinder resulting in volumetric heat generation rate 
of qm. The cylinder is cooled by convection at its surface. The heat transfer 
coefficient is considered as h and the ambient temperature is considered as T∞. The 
objective is to determine the transient temperature of the cylinder.

![image](https://user-images.githubusercontent.com/111849605/202916632-87f27e67-30ce-47da-aca1-85c195ad8645.png)

Assumptions:
1. One dimensional conduction.
2. Uniform h and T∞.
3. Constant conductivity.
4. Constant diffusivity.
5. Negligible end effect.


Governing Equations:
To make the convection boundary condition homogeneous, we introduce the 
following temperature variable
θ (r,t) = T(r,t) - T∞.

Based on the above assumptions, gives
![image](https://user-images.githubusercontent.com/111849605/202916684-d1567327-02f0-4df0-af1b-827bedbc45ed.png)

Boundary and initial conditions:
![image](https://user-images.githubusercontent.com/111849605/202916698-af4de2b0-91d0-48af-802c-f905b65733be.png)

Solution:
Since the differential equation s non-homogeneous, we assume a solution of 
the form
𝜃(𝑟,𝑡) = 𝜑(𝑟,𝑡) + ∅(𝑟)       (a)

Note that Ψ(r-t) depends on two variables while ϕ(r) depends on one 
variable. Substituting (a) into eq. (A)

![image](https://user-images.githubusercontent.com/111849605/202916775-2f6bba63-c6d3-427b-a271-5f4f25a00214.png)   (b)

The next step is to split (b) into two equations, one for Ψ(r-t) and the other 
for ϕ(r). Let..

![image](https://user-images.githubusercontent.com/111849605/202916818-234dcd21-bb41-4d11-ba03-ad559e0b231a.png)  (c)
![image](https://user-images.githubusercontent.com/111849605/202916837-365981ec-514c-4567-be2e-fedc62962083.png)  (d)

To solve equations (c) and (d) we need two boundary conditions for each 
and an initial condition for (c). Substituting (a) into boundary condition (1)

![image](https://user-images.githubusercontent.com/111849605/202916857-25467901-9a32-4a32-8ce6-e0e984838731.png)


