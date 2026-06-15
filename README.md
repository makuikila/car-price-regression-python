# Car Price Prediction with Linear Regression

> Academic machine learning project for predicting car prices using regression models in Python.

## Project Overview

This project solves a regression task for car price prediction. It includes data loading, exploratory analysis, preprocessing of categorical and numerical variables, feature preparation, model training, and evaluation using common regression metrics.

## Dataset

The project uses `CarPrice_Assignment.csv`, included in the `data/` folder.

## Technologies

| Category | Tools |
|---|---|
| Language | Python |
| Notebook | Jupyter / Google Colab |
| Data Analysis | pandas, NumPy |
| Machine Learning | scikit-learn |
| Visualization | Matplotlib, Plotly, Seaborn |

## Models and Metrics

The notebooks include regression experiments with:

- Linear Regression
- Ridge Regression
- Lasso Regression

Evaluation metrics include:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² score

## Repository Structure

```text
car-price-regression-python/
├── README.md
├── LICENSE
├── requirements.txt
├── .gitignore
├── data/
│   └── CarPrice_Assignment.csv
└── notebooks/
    ├── car_price_regression.ipynb
    └── car_price_regression_example.ipynb
```

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook notebooks/car_price_regression.ipynb
```

If running from the notebook folder, adjust the dataset path to `../data/CarPrice_Assignment.csv` if necessary.

## Skills Demonstrated

- Regression modeling
- Feature engineering
- Encoding categorical variables
- Model comparison
- Regression metric interpretation

## Author

**Manassé Makuikila Lusaku**

## License

MIT License
