# Machine Learning Algorithms from Scratch

## Repository Status

This repository contains a migrated version of the original project.

The project was initially developed on a previous GitHub account after losing access to it. To continue development, the repository has been recreated here with some cleanup and improvements.

All future updates and maintenance will be made in this repository.

---

## Overview

This repository is a **long-term, evolving project** focused on implementing Machine Learning algorithms **from scratch** and **with optimized/library-based approaches** side by side.

The main idea is not to provide a fixed, final framework, but to **continuously grow** a collection of ML algorithms while exploring:

* How algorithms work internally (pure Python / minimal dependencies)
* How performance improves using optimized numerical libraries
* How these implementations compare to well-established libraries

This repository will be updated over time as new algorithms, datasets, benchmarks, and experiments are added.

---

## Goals

* Build a deep understanding of ML algorithms by implementing them manually
* Compare **clarity vs performance** trade-offs
* Keep implementations readable, educational, and reproducible
* Provide lightweight benchmarks for practical comparison

---

## Philosophy

* No heavy abstractions
* No premature optimization
* Algorithms are implemented incrementally
* Structure may evolve as the project grows

This repository is intended as a **learning-oriented and experimental codebase**, not a production-ready ML framework.

---

## Project Structure

The repository is organized by learning paradigm and algorithm family:

* `supervised/`

  * Classification algorithms (e.g. KNN)
* `unsupervised/`

  * Clustering algorithms (e.g. K-Means)
* `datasets/`

  * Synthetic datasets used for benchmarks
* `benchmarks/`

  * Lightweight benchmark scripts for performance comparison

Each algorithm typically includes:

* A **pure Python** implementation
* An **optimized** (NumPy-based) implementation
* A **scikit-learn reference** wrapper (when applicable)

All implementations aim to expose a similar API for fair comparison.

---

## Benchmarks

Each algorithm directory contains benchmark scripts that compare:

* Pure Python implementation
* Optimized NumPy implementation
* Scikit-learn reference implementation

Benchmarks are intentionally **lightweight** and focus on:

* Relative performance
* Algorithmic differences
* Implementation overhead

They are **not** intended as definitive performance measurements.

---

## Notes

* Some sections or directories may be empty or incomplete at times
* APIs are not guaranteed to be stable
* Benchmarks focus on relative comparison, not absolute performance
* This repository prioritizes **learning clarity over production robustness**

---

## License

[MIT License](LICENSE)
