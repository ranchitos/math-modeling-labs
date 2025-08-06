# Logistic Budget Model

This project models my daily spending using a logistic differential equation with a decreasing carrying capacity. It compares theoretical predictions to real data, and explores curve fitting to estimate model parameters from past behavior.

## Features

- Uses `solve_ivp` from SciPy to simulate logistic decay
- Reads real spending data using `pandas`
- Calibrates the model with parameter fitting
- Visualizes balance vs. time with Plotly

## Status

Currently exploratory. Model performs well but has limitations (does not incorporate time-varying behavior yet).