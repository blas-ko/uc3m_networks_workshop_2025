# Dynamics on Networks
**Blas Kolic 2025**

In this tutorial, we will implement some of the most famous models for dynamics on networks. We will analyze their behavior under different assumptions, such as their equilibrium distributions, their critical regimes for extended diffusion, and strategies to exploit network structure to maximize or minimize spreading.

First, we will implement each of the models by hand, and visualize them in the Karate club network to gain some intuition. Then, we will move into a slightly larger real network and test different immunization and seeding strategies using epidemiological models of diffusion.

**Outline of the tutorial**
1. **Network dynamics models implementation**: including:
   1. The random walker
   2. Independent cascade model
   3. Epidemiological SIR model
2. **Immunization and seeding strategies**: We will see how to maximize/minimize spread when the dynamics follow the SIR model
3. **Optional exercises**