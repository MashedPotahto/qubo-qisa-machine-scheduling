[![DOI](https://zenodo.org/badge/1185873498.svg)](https://doi.org/10.5281/zenodo.19104205)

# QUBO-Based Quantum-Inspired Simulated Annealing for Multi-Machine Energy Scheduling

**Authors:** I.J. Mesoga, Ziv Atienza, David Marcelino
**Institution:** [Your school name]
**Course:** Introduction to Metaheuristics

## Overview
This repository contains the Python implementation of a QUBO-based quantum-inspired simulated annealing (QI-SA) framework for scheduling multi-machine ON/OFF states in Philippine discrete manufacturing facilities. The objective is to minimize peak electrical demand and total electricity cost under the Meralco General Power Secondary tariff.

## Contents
- `NEOZEP-RESEARCH-CO_FinalReport.ipynb` — Full implementation including QUBO formulation, brute-force benchmark, QI-SA solver (30 seeds), and results report

## Key Parameters
- 10 machines, K = 8 minimum active constraint
- λ = 20,000 PHP penalty weight
- Meralco demand charge: PHP 235.15/kW/month
- T_start = 10,000 | T_end = 0.01 | Sweeps = 10,000

## Results
- Baseline cost: PHP 139,777.20
- Optimal cost: PHP 7,881.43 (94.36% reduction)
- Optimality gap: 0.0000% across 30 independent seeds

## Requirements
Run on Google Colab or any environment with `numpy` and `plotly` installed.
