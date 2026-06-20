# Clustering and Initialization

Final project for the Statistical Methods for Machine Learning course at the University of Milan, held by Professor Nicolò Cesa-Bianchi.

## Overview

This project studies the impact of initialization on clustering performance by implementing and comparing the `k-means` and `k-means++` algorithms from scratch. The two algorithms are tested on three different datasets:

- A synthetic 2D dataset with well-separated clusters
- The MNIST dataset (subset of 2000 samples)
- A synthetic 2D dataset with overlapping clusters (project extension)


The full analysis and results are presented in the project report (`report.pdf`).

## Repository structure

- `MLProject.ipynb` — Jupyter notebook containing the full implementation and experiments
- `Final Project Report - Maspero Federico.pdf` — Project report with methodology, results and conclusions
- `README.md` — This file

## Requirements

- Python 3.x
- `numpy`
- `matplotlib`
- `scikit-learn` (for loading the MNIST dataset)

## How to run

Open the Jupyter notebook and run the cells in order. The random seeds used in the experiments ensure that the results are reproducible.

## Author

Federico Maspero — Department of Computer Science, University of Milan