# Value at Risk for Options

---

## Project Overview

This project implements and analyzes risk management methodologies, focusing on the **Cornish-Fischer Value-at-Risk (VaR)** approach for a portfolio containing a single option. Theoretical derivations are complemented by computational simulations to demonstrate the applicability of these concepts.

---

## Key Features

- **Theoretical Calculations**:
  - Delta-Gamma-Speed approximation for VaR.
  - Polynomial representations of portfolio moments.
  - Application of the Cornish-Fischer expansion for skewness and kurtosis corrections.

- **Practical Implementation**:
  - Simulations for portfolio returns.
  - Computation of moments (mean, variance, skewness).
  - Visualization of results for various confidence levels.

---

## Requirements
- Python 3.9+
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`

---

## Code Structure
The project is organized as follows:

```plaintext
Value-at-Risk-Options/
├── notebook/ # Jupyter Notebook for VaR calculations and simulations.
│   ├── .ipynb_checkpoints/ # Auto-saved checkpoints for the notebook.
│   └── Value_at_Risk_Options_Notebook.ipynb # Main notebook for implementation.
├── LICENSE # License for the project.
└── README.md # Project documentation.
```