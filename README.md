# Oligopoly-model-with-three-time-delays
# Oligopoly Model with Two Time Delays (Mathematica)

This repository contains a Mathematica implementation of a dynamic Cournot oligopoly model with two discrete time delays.

## Description

The model simulates `n` firms adjusting their output levels over time with memory. Three delays are introduced to capture different types of reaction lags. The system explores how varying the adjustment speed `α` affects the system's stability and chaotic behavior.

## Features

- Bifurcation diagram over parameter α
- Lyapunov exponent computation
- Random initial condition
- Jacobian-based analysis

## Files

- `main_code.m`: The complete Mathematica model
- `README.md`: Project documentation

## Usage

1. Open the `main_code.m` file in Mathematica.
2. Set parameters like:
   - `nfirme` (number of firms)
   - `T0`, `T1`, `T2` (delay times)
   - `a0`, `a1`, `be`, `de` (model constants)
3. Run the script to generate bifurcation and Lyapunov plots.

## License

MIT License
