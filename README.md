# Tipping-Point-Paper

[![arXiv](https://img.shields.io/badge/arXiv-2509.01622-b31b1b.svg)](https://arxiv.org/abs/2509.01622)

This repository accompanies the research paper:

> **Finite-Sample Non-Parametric Bounds with an Application to the Causal Effect of Workforce Gender Diversity on Firm Performance**  
> *Grace Lordan & Kaveh Salehzadeh-Nobari (2025)*  
> https://arxiv.org/abs/2509.01622

It provides all datasets, code, and Monte-Carlo experiments required to
replicate the empirical analysis and identification results in the paper.

---

## What This Repository Provides

- Non-parametric identification of treatment effects at tipping points  
- Support-based Manski bounds  
- DKW-calibrated hybrid bounds for finite-sample validity  
- Latent conditional expectation bounding
- Monte-Carlo validation across multiple data-generating processes  
- End-to-end empirical replication of the paper’s figures & tables  
- Publication-ready plots and LaTeX exports

---

## Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/kavehsn/Tipping-Points-Paper.git
cd Tipping-Points-Paper
```
### 2️⃣ Create & activate environment

```bash
conda env create -f tipping_environment.yml
conda activate tipping
```
### 3️⃣ Launch JupyterLab

```bash
jupyter lab
```

