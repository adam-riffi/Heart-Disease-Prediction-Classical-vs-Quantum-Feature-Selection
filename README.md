# Heart Disease Feature Selection using Classical and Quantum Methods

This project compares two approaches to feature selection for a classification task on the Heart Disease dataset:

- **Classical method**: ANOVA F-score ranking combined with logistic regression.
- **Quantum-inspired method**: QUBO formulation solved with QAOA using Qiskit.

## Dataset

The dataset used is the UCI Heart Disease dataset (`heart.csv`), which includes various patient health indicators and a binary target variable indicating presence or absence of heart disease.

## Methods

- **Classical**: Uses `SelectKBest` with F-score and evaluates subsets of features using logistic regression.
- **Quantum**: Encodes feature scores as a QUBO problem and solves it using QAOA from Qiskit.

## How to Run

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Open the notebook:

```bash
jupyter notebook HeartDisease_FeatureSelection_QAOA_WithConclusion.ipynb
```

## Results

Both methods were evaluated using logistic regression accuracy. The quantum approach using QAOA achieved competitive results compared to the classical method.

## Requirements

See `requirements.txt` for package list and versions.

## License

This project is for educational purposes only.
