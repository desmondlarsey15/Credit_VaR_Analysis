# Monte Carlo Credit Risk Simulator for Corporate Bond Portfolios

## Overview
This project implements a Monte Carlo simulation framework to model credit risk in a portfolio of corporate bonds. The model simulates correlated credit rating migrations and default events across multiple bonds to estimate portfolio loss distributions.

The simulation uses stochastic processes and probability transition thresholds to replicate how credit ratings evolve over time under uncertainty.

The goal of the project is to demonstrate practical quantitative finance techniques used in credit risk modeling, portfolio risk management, and stress testing.

---

## Key Features

- Large-scale Monte Carlo simulation (1,000,000 scenarios)
- Correlated credit migration modeling
- Default probability modeling
- Multi-bond portfolio risk analysis
- Loss distribution visualization
- Portfolio credit exposure analysis

---

## Model Framework

The model simulates the evolution of bond credit ratings across the following states:

AAA → AA → A → BBB → BB → B → CCC → Default

Each rating state has an associated transition probability representing the likelihood of migrating to another rating or defaulting.

A **correlation structure** is introduced between bonds to model systemic risk affecting multiple issuers simultaneously.

The simulation process:

1. Generate correlated random variables
2. Map variables to rating transition thresholds
3. Simulate rating migration or default
4. Calculate bond value under each scenario
5. Aggregate portfolio losses
6. Analyze the distribution of outcomes

---

## Technologies Used

- Python
- NumPy
- SciPy
- Pandas
- Matplotlib
- Seaborn
- Monte Carlo Simulation
- Credit Risk Modeling

---

## Output

The model produces:

- Portfolio loss distribution
- Probability of default events
- Expected loss estimates
- Visualization of simulated outcomes

Example outputs include histograms and density plots showing the distribution of portfolio losses.

---

## Why This Project Matters

Credit risk modeling is central to financial institutions including:

- Banks
- Asset managers
- Hedge funds
- Rating agencies
- Insurance companies

Monte Carlo simulations are widely used for:

- Portfolio credit risk analysis
- Stress testing
- Capital adequacy assessment
- Structured credit product pricing

---

## Future Improvements

Potential enhancements include:

- Multi-period credit migration modeling
- Structural credit risk models (Merton framework)
- Larger bond portfolios
- Credit spread modeling
- Value-at-Risk (VaR) and Expected Shortfall calculations

---

## Author

Desmond Larsey  
Quantitative Finance | Risk Modeling | Portfolio Analytics
