# Neural Network From Scratch

A small notebook-based neural-network project that uses NumPy and pandas to classify handwritten digits.

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,jupyter,numpy,pandas&theme=light" alt="Python, Jupyter, NumPy, and pandas" />
</p>

## Overview

The repository contains a single model notebook and CSV data files:

- `model.ipynb` — model development and experiments.
- `train.csv` — training data.
- `test.csv` — test data.

## Preview

![Neural-network notebook chart](https://noah-readme-assets-v3.vercel.app/Neural-Network-From-Scratch/nb__model.ipynb__cell17__out1.png)

## Usage

Open `model.ipynb` in Jupyter and run the notebook cells with `train.csv` and `test.csv` available in the repository root.

The notebook and its datasets are the primary project links; no browser demo is provided.

## Status

This repository is a compact notebook project. No automated test suite or environment specification is included.

> [!TIP]
> Keep `train.csv` and `test.csv` beside `model.ipynb` when opening the notebook; the documented workflow expects repository-root data paths.

## Workflow

```mermaid
flowchart LR
    A[train.csv and test.csv] --> B[model.ipynb]
    B --> C[NumPy and pandas preprocessing]
    C --> D[Neural-network training]
    D --> E[Handwritten-digit classification]
```
