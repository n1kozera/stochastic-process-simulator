# stochastic-process-simulator
A Python library for simulating stochastic processes via Monte Carlo methods, comparing empirical and theoretical moments, and visualizing probability distributions. Designed to build intuition around randomness, convergence, and probabilistic modeling.
# 🎲 Probability Simulator Library

A lightweight Python library for **simulating stochastic processes**, validating **theoretical probability results**, and **visualizing empirical distributions** through large-scale Monte Carlo experiments.

This project is built for people who care about the **why** behind randomness—not just calling `.fit()` and hoping for the best.

---

## 🚀 Features

- **Random Walk Simulation**
  - Generate **10,000+ independent paths**
  - Fully configurable step distribution, drift, and horizon
  - Supports reproducible experiments via seeding

- **Empirical vs Theoretical Analysis**
  - Compute empirical:
    - Mean
    - Variance
    - Higher moments (skewness, kurtosis)
  - Compare against **closed-form theoretical results**
  - Quantify convergence via Law of Large Numbers

- **Visualization**
  - Path evolution plots
  - Distribution histograms
  - Empirical vs theoretical density overlays
  - Built using `matplotlib` for transparency and control

---

## 🧠 Why This Exists

Most probability libraries:
- hide the math  
- abstract away randomness  
- encourage copy-paste modeling  

This library is intentionally **explicit**:
- You see the process
- You measure convergence
- You verify theory with simulation
cd probability-simulator
pip install -r requirements.txt
