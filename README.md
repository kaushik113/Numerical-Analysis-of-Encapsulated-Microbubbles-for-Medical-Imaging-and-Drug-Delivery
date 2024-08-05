# Numerical-Analysis-of-Encapsulated-Microbubbles-for-Medical-Imaging-and-Drug-Delivery

## Overview

This project focuses on the mathematical modeling of encapsulated microbubbles used in medical imaging and drug delivery. Encapsulated microbubbles enhance ultrasound imaging contrast and facilitate targeted drug delivery. Understanding how encapsulation elasticity affects microbubble dynamics is crucial for optimizing their performance.

## Objectives

1. Review existing literature on encapsulated microbubbles.
2. Analyze fundamental equations and properties of microbubbles.
3. Understand factors influencing microbubble behavior.
4. Develop a mathematical model for microbubble behavior.
5. Formulate and solve governing equations for microbubble dynamics.
6. Implement numerical simulations in MATLAB.
7. Analyze the impact of varying parameters, particularly encapsulation elasticity.
8. Investigate the effects of medium saturation levels.

## Physical Model

The model considers the following properties:

- **Encapsulation Properties:** Elasticity (Es) and permeability (hg) of the encapsulating material.
- **Gas Behavior:** Solubility and diffusivity of the gas inside the microbubble.
- **Surface Tension:** Affects bubble stability and dissolution.
- **Equilibrium Conditions:** Influenced by surface tension, encapsulation elasticity, and gas properties.

## Assumptions

1. Steady-state conditions.
2. Spherical symmetry of microbubbles.
3. Neglect of convection effects.
4. Linear model for gas permeability.
5. Isotropic behavior of encapsulating material.

## Governing Equations

1. **Diffusion Equation:** Describes gas transport from the microbubble to the surrounding medium.
2. **Mass Conservation:** Relates bubble growth and dissolution to gas concentration changes.
3. **Pressure Inside the Bubble:** Includes Laplace pressure and gas concentration.
4. **Dissolution Equation:** Describes the rate of change of bubble radius over time, considering surface tension and elasticity.

## Parameters

Key parameters include bubble radius, gas concentration, permeability, diffusivity, surface tension, Ostwald coefficient, and more.

## Solution Methodology

1. **Analytical Analysis:** Determines equilibrium radius based on surface tension and encapsulation elasticity.
2. **Numerical Analysis:** Uses MATLAB to simulate bubble dynamics in different mediums and analyze the impact of elasticity on stability.
3. **Numerical Integration:** Implements the Runge-Kutta method to solve differential equations for bubble radius evolution over time.

## Results

- **For f < 1:** Bubble dissolution occurs eventually.
- **For f = 1:** Bubble reaches a stable radius if elasticity exceeds surface tension.
- **For f > 1:** Oversaturation can stabilize the bubble and counteract surface tension effects.


