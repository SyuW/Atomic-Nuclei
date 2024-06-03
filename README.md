# Atomic-Nuclei
Exploring connections between random matrices and nuclear physics.

There is a surprising connection between random matrix theory and the energy spacings of atomic nuclei. The usage of random matrices for studying atomic nuclei
was introduced by physicist Eugene Wigner in the 1950s. 

In this repository, I tackle the simplest case of a two-level system, looking at the level statistics of 2-by-2 symmetric or Hermitian random matrices (where each of the free components are drawn from a Gaussian distribution), although I plan to generalize to the n-by-n case in the future. The `.nb` notebook performs the tedious calculations when deriving the exact expression of the level spacing distribution. The `.py` notebook checks the validity of the analytical expression with a simple Monte Carlo simulation.

![image](https://github.com/SyuW/Atomic-Nuclei/assets/49294470/727b2e2b-234e-4372-bb6e-a1e0302b3858)

As you can see, they agree pretty well! See https://en.wikipedia.org/wiki/Random_matrix#Gaussian_ensembles for more. There is some nice exposition about the universality of the distribution function given in this Stackexchange post: https://physics.stackexchange.com/questions/13266/how-come-random-matrices-can-predict-energy-spectra-of-heavy-atoms.
