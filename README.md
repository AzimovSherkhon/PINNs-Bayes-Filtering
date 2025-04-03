# PINNs Bayes
## This reposity contains the code of the paper "Integrating Physics-Informed Neural Networks with Bayesian inference for nonlinear filtering"

## Author: Azimov Sherkhon

This repository presents an approach to state estimation in nonlinear dynamical systems by integrating **Physics-Informed Neural Networks (PINNs)** with **Bayesian Inference**, referred to as "**PINNs Bayes**." The method utilizes PINNs to solve the **Forward Kolmogorov Equation**, governing the time evolution of the probability density function (pdf), providing an accurate prior for Bayesian state estimation.

The approach is validated using a **one-dimensional stochastic double-well potential model**, capturing the nonlinear and bistable dynamics inherent in complex systems. Additionally, **PINNs Bayes** is benchmarked against traditional methods, including approximate techniques such as:

- **Ensemble Kalman Filter (EnKF)**
- **Particle Filter (PF)**
- **Finite Difference Method with Bayesian Inference (FDM Bayes)**

## Overview

- **Objective**: State estimation in nonlinear dynamical systems.
- **Methodology**: Integration of PINNs with Bayesian Inference to estimate system states accurately.
- **Validation**: A one-dimensional stochastic double-well potential model.
- **Comparison**: Benchmarking against EnKF, PF, and FDM Bayes (all codes included).

## Features

- Accurate prior estimation using PINNs.
- Bayesian inference for posterior state estimation.
- High-performance benchmarks against traditional methods.
- Open-source code for reproduction and further research.

## Citation
If you use this code for your research, please cite our paper:
