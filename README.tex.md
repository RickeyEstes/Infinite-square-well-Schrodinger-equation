# Infinite-square-well-Schrodinger-equation
Analytical solution to the Time-Dependent Schrodinger equation for a particle in an infinite square well.

### Animation speed up 3000%
![time_dependent_3000](https://github.com/timothypholmes/Infinite-square-well-Schrodinger-equation/blob/master/time_dependent_3000.gif)

## The theory

$$
1 = \int_{-\infty}^{\infty} A^{2}|\psi(x)|^{2} dx.
$$

$$
\varphi_n(x) = \sqrt{\frac{2}{L}}*sin\Big(\frac{n\pi x}{L}\Big).
$$

$$
E_n = \frac{n^2\pi^2 \hbar^2}{2mL^2}.
$$

$$
c_n = \int_{-\infty}^{\infty} \varphi_n(x)^{*} \psi(x,0) dx.
$$

$$
\psi(x,t) = \sum_{n}^{500} c_{n} e^{-iE_nt/\hbar}\varphi_{n}(x).
$$

### Animation real time
![time_evolution](https://github.com/timothypholmes/Infinite-square-well-Schrodinger-equation/blob/master/time_evolution.gif)