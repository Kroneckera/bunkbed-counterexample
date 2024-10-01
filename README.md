# The Bunkbed Conjecture Counterexample

This repository contains a Jupyter Notebook titled `bunkbed_counterexample.ipynb`, which constructs a counterexample to the bunkbed conjecture. The notebook is based on a joint paper authored by Nikita Gladkov, Igor Pak, and Aleksandr Zimin.

## Purpose

The primary goal of this notebook is to computationally verify the results presented in the paper, specifically to support the proof of Lemma 3.2. Since the proof involves a cumbersome, case-by-case analysis, we used computational tools to verify its correctness and ensure the robustness of our findings.

In addition, we check the validity of the approach for smaller graphs to ensure that the computational framework generalizes well beyond the specific cases considered in the paper. While our proof requires large graphs, we demonstrate that the number of vertices required is actually much smaller than initially expected.

## Requirements

To run this notebook, you will need the following Python packages:
  - `numpy`
  - `sympy`

These packages can be installed via pip:

```bash
pip install numpy sympy
