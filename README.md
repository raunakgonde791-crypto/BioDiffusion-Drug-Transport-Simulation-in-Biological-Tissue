# BioDiffusion: Drug Transport Simulation in Biological Tissue

## Overview
BioDiffusion is a computational model that simulates the spatial and temporal diffusion of a drug within biological tissue. The model is based on numerical approximation of diffusion dynamics and incorporates realistic factors such as tissue heterogeneity and drug decay.

## Motivation
Understanding how drugs propagate through biological tissue is essential in drug delivery, pharmacokinetics, and biomedical engineering. This project provides a simplified but insightful visualization of these processes.

## Features
- 2D drug diffusion simulation
- Spatially varying diffusion coefficient (tissue heterogeneity)
- Drug decay to simulate metabolic effects
- Gaussian initial drug distribution
- Animated heatmap visualization (GIF output)

## Tech Stack
- Python
- NumPy
- Matplotlib

## Simulation Details
- Grid-based numerical model
- Finite difference approximation of diffusion
- Dynamic concentration updates over time
- Boundary constraints to simulate confined tissue region

## How to Run

```bash
pip install -r requirements.txt
python src/simulation.py
