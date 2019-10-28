# Poincaré Recurrence, Cycles and Spurious Equilibria in Gradient-Descent-Ascent for Non-Convex Non-Concave Zero-Sum Games
Lampros Flokas, Emmanouil V. Vlatakis-Gkaragkounis, Georgios Piliouras

33rd Annual Conference on Neural Information Processing Systems (NeurIPS 2019)

## Abstract
We study a wide class of non-convex non-concave min-max games that generalizes over standard bilinear zero-sum games. In this class, players control the inputs of a smooth function whose output is being applied to a bilinear zero-sum game. This class of games is motivated by the indirect nature of the competition in Generative Adversarial Networks, where players control the parameters of a neural network while the actual competition happens between the distributions that the generator and discriminator capture. We establish theoretically, that depending on the specific instance of the problem gradient-descent-ascent dynamics can exhibit a variety of behaviors antithetical to convergence to the game theoretically meaningful min-max solution. Specifically, different forms of recurrent behavior (including periodicity and Poincaré recurrence) are possible as well as convergence to spurious (non-min-max) equilibria for a positive measure of initial conditions. At the technical level, our analysis combines tools from optimization theory, game theory and dynamical systems.

## Code
The code is uisng a combination of Jupyter and Mathematica notebooks.

For the former you can install the dependencies via conda
```shell
conda env create -f environment.yml
```

For the latter you need to install [Mathematica](https://reference.wolfram.com/language/tutorial/InstallingMathematica.html)

The outputs are in the figures folder.
