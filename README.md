# Chaos and Dynamical Systems in Python

Python notebooks exploring chaos in the logistic map and the two-dimensional Hénon map, written for a University of Sheffield mathematics group project.

## What's in this repository

| File | What it does |
| --- | --- |
| `henon_map.ipynb` | Plots the Hénon attractor (a = 1.4, b = 0.3) and shows how it forms by stretching and folding a line of points over five iterations. |
| `logistic_sensitivity.ipynb` | Follows two logistic map orbits (r = 3.75) that start 0.000001 apart, and plots how fast they separate. |
| `logistic_orbit.ipynb` | A single logistic map orbit at r = 2.75, which settles to a stable fixed point. |

## Findings

- **Hénon map:** the orbit settles onto a thin, layered curve called a strange attractor, rather than filling the plane. Stretching and folding keeps points bounded while pulling nearby points apart.
- **Sensitivity to initial conditions:** the two orbits stay together for a while, then become completely different after about 55 iterations. On a log scale the gap grows along a straight line, which means exponential growth.
