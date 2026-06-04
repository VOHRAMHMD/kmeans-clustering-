# K-means and K-means++ Clustering

Experimental project for the course **Statistical Methods for Machine Learning**
A.Y. 2025/26 — Università degli Studi di Milano
Instructor: Nicolò Cesa-Bianchi

## Assignment
Assignment 5 — Clustering and Initialization
Based on the paper: *k-means++: The Advantages of Careful Seeding* (Arthur & Vassilvitskii, SODA 2007)

## Description
This project implements and compares K-means and K-means++ clustering algorithms
from scratch, studying the impact of initialization on clustering performance.

## Datasets
- **Synthetic (separated):** 300 points, 4 well-separated Gaussian clusters
- **Synthetic (overlapping):** 300 points, 4 overlapping Gaussian clusters
- **MNIST:** 3000 samples, 784 features (real-world high-dimensional dataset)

## Results Summary
| Dataset | Algorithm | Mean Inertia | Std |
|---|---|---|---|
| Synthetic (separated) | K-means | 1178.71 | 1363.12 |
| Synthetic (separated) | K-means++ | 514.85 | 457.13 |
| Overlapping clusters | K-means | 3486.41 | 482.23 |
| Overlapping clusters | K-means++ | 3487.04 | 483.90 |
| MNIST (high-dim) | K-means | 115606.31 | 517.77 |
| MNIST (high-dim) | K-means++ | 115704.07 | 559.32 |

## How to Run
1. Clone the repository
2. Install dependencies: