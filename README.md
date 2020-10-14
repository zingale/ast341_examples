# AST 341 Examples

Some simple notebooks and codes demonstrating stellar physics concepts for AST 341.

## Simple Stellar Model

The notebook `simple_stellar_model.ipynb` computes various properties
of a star given its mass profile.  This was part of homework #1.  You
can explore this notebook in binder with the following link:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/zingale/ast341_examples/master?filepath=simple_stellar_model%2Fsimple-stellar-model.ipynb)

(it may take a few minutes to start up)

## Ideal Gas

The notebook `ideal_gas.ipynb` computes the ideal gas law by
integrating the Maxwell-Boltzmann distribution (in the appropriate
integral).  This was part of homework #2.  You can explore this
notebook in binder with the following link:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/zingale/ast341_examples/master?filepath=ideal_gas%2Fideal_gas.ipynb)

(it may take a few minutes to start up)


## Nuclear Reactions

You can replay the interactive exploration of the transition from pp -> CNO -> hot-CNO with this
notebook:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pynucastro/pynucastro/main?filepath=examples%2Fpp-CNO-example.ipynb)


## Orbits

The notebook `orbits.ipynb` shows how to integrate the equations of
motion for Earth orbiting around the Sun using Euler's method.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/zingale/ast341_examples/master?filepath=orbits_example%2Forbits.ipynb)

(it may take a few minutes to start up)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/zingale/ast341_examples/blob/master/orbits_example/orbit.ipynb)


## Polytropes

The notebook `lane-emden.ipynb` integrates the Lane-Emden equation for
polytropes and explores the solution.  A class implementing
Runge-Kutta integration is provided, as well as an alternate solution
that uses the SciPy `solve_ivp()` method.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/zingale/ast341_examples/blob/master/polytropes/lane-emden.ipynb)

