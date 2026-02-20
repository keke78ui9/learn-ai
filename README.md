# learn-ai

A collection of hands-on learning exercises covering **AI**, **Machine Learning**, and **LLMs**.

## Repository Structure

Each top-level folder is a self-contained learning exercise. Every exercise folder contains:
- A **sample dataset** (CSV or similar format)
- A **Jupyter notebook** (`.ipynb`) with step-by-step analysis, model training, and evaluation

```
learn-ai/
├── ML_regression_01/          # Linear Regression — House Price Prediction
│   ├── dataset.csv            # Synthetic house-price dataset
│   └── regression_analysis.ipynb
└── ...                        # More exercises coming soon
```

## Exercises

| Folder | Topic | Algorithm |
|--------|-------|-----------|
| [ML_regression_01](./ML_regression_01/) | House Price Prediction | Linear Regression |

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/keke78ui9/learn-ai.git
   cd learn-ai
   ```
2. Install dependencies (Python 3.8+):
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Open any exercise notebook:
   ```bash
   cd ML_regression_01
   jupyter notebook regression_analysis.ipynb
   ```
