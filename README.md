# Option Pricing : From Monte-Carlo to Black-Scholes

This repository presents the implementation of two classic quantitative finance methods for pricing European options

## Project Overview

I chose to generate $M = 1000$ different paths to see how fast the Monte-Carlo estimator converges.
The project explores and compares different pricing models, focusing on :

<img width="1404" height="913" alt="image" src="https://github.com/user-attachments/assets/3d47bc1b-8c7f-4d0f-9aa2-3447c20cd698" />


**Black-Scholes Analytical Model** : Using closed-form formulas to evaluate the theoretical price of an option based on Geometric Brownian Motion

**Monte-Carlo Simulation** : A numerical method simulating numerous asset trajectories to estimate the option price via the empirical expected value of discounted payoffs

**Convergence Study** : Analyzing the convergence of the Monte-Carlo simulations towards the theoretical Black-Scholes prices.

**Limits :** The model Black-Scholes in this form is not relevant because it uses a constant volatility, which is not true in reality

<img width="1407" height="1415" alt="image" src="https://github.com/user-attachments/assets/e467ecd8-8f10-48ef-9f48-5e100554207c" />


##  Documentation

[📖 Click here to read the full report in French (PDF)](https://github.com/mehdi-belhamiti/Option-Pricing-Models-Black-Scholes-vs-Monte-Carlo-Simulations/blob/main/Mode%CC%80le%20Black-Scholes%20et%20Me%CC%81thode%20de%20Monte-Carlo-Finance.pdf)

## Technologies and Libraries Used
* **Python**
* **NumPy**
* **SciPy (`scipy.stats.norm`)** : For the normal distribution cumulative density functions in Black-Scholes
* **Matplotlib** : For visualizing the simulated asset price trajectories.

---
*Author : Mehdi Belhamiti*
