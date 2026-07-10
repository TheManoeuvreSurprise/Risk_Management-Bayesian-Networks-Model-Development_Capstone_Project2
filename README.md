# Bayesian Networks & Hidden Markov Models – Mini Capstone GWP2 (MScFE 660)
**Risk Management** 

Second part of the mini-capstone series focused on **Probabilistic Graphical Models for Crude Oil Price Forecasting**.

---

## Project Objectives

- Deep dive into Hidden Markov Model (HMM) algorithms
- Implementation of regime detection (Bull, Bear, Stagnant)
- Bayesian Network structure learning and parameter estimation
- Literature review + methodology documentation

---

## Key Tasks Completed

### Issue 1: HMM Algorithms
- Forward & Backward algorithms (pseudocode + toy example)
- Viterbi algorithm (pseudocode + toy example)
- Baum-Welch algorithm (pseudocode + toy example)

### Issue 2: Regime Identification
- Bull, Bear, and Stagnant market regimes with illustrations

### Issue 3–6: Methodology Documentation
- Updated definition of Hidden Markov Models
- Macro research, data cleaning, and indicator selection
- Regime process using `hmms` library
- Network training and validation using `pgmpy`

### Issue 7–9: Advanced Implementation
- Latent state interpretation
- Hill Climb search minimal working example

---

## Technical Stack

- `pgmpy` – Bayesian Networks
- `hmms` – Hidden Markov Models
- `pandas`, `numpy`, `matplotlib`
- Custom implementations of HMM algorithms

---

## Repository Contents

- `MScFE_660_GWP2_Bayesian_Model_Development.ipynb` ← Main executable notebook
- `report.pdf` ← Cohesive Literature Review + Methodology section
- `requirements.txt`
- `figures/` ← Regime illustrations and model diagrams
- `README.md`

---

## How to Run

```bash
git clone https://github.com/yourusername/MScFE-660-Bayesian-Networks-Model-Development-GWP2.git
cd MScFE-660-Bayesian-Networks-Model-Development-GWP2
pip install -r requirements.txt
jupyter notebook MScFE_660_GWP2_Bayesian_Model_Development.ipynb
