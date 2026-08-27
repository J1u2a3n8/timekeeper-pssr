# timekeeper-pssr

> Time Series Analysis with PSSR

![Language](https://img.shields.io/github/languages/top/J1u2a3n8/timekeeper-pssr)
![License](https://img.shields.io/github/license/J1u2a3n8/timekeeper-pssr)
![Last Commit](https://img.shields.io/github/last-commit/J1u2a3n8/timekeeper-pssr)
![Stars](https://img.shields.io/github/stars/J1u2a3n8/timekeeper-pssr?style=social)
![Issues](https://img.shields.io/github/issues/J1u2a3n8/timekeeper-pssr)

## Description

Time series forecasting and anomaly detection using Periodic Seasonal Stochastic Regression (PSSR). Includes trend decomposition, seasonal adjustment, and real-time monitoring capabilities.

## Architecture

TS Pipeline: Ingestion → Decomposition (Trend/Seasonal/Residual) → PSSR Modeling → Forecasting → Anomaly Detection → Alerting

## Quick Start

### Prerequisites

Python 3.10+, pip/poetry, Jupyter Lab

### Installation

```bash
# Clone
git clone https://github.com/J1u2a3n8/timekeeper-pssr.git
cd timekeeper-pssr

pip install -r requirements.txt
# jupyter lab
```

### Usage

```bash
jupyter notebook notebooks/timekeeper-pssr.ipynb
```

## Testing

```bash
pytest tests/
```

## Project Structure

```
timekeeper-pssr/
├── src/              # Main source code
├── tests/            # Unit/integration tests
├── docs/             # Documentation
├── .github/          # CI/CD workflows
└── README.md
```

## Tech Stack

Python, Pandas, Statsmodels, SciPy, NumPy, Plotly, Jupyter

## License

This project is licensed under the **MIT License** - see [LICENSE](LICENSE) for details.

## Author

**J1u2a3n8** - [GitHub](https://github.com/J1u2a3n8) - [LinkedIn](https://linkedin.com/in/juanluiscanedo)

---

⭐ If you found this project useful, give it a star!
