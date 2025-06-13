# Malaria-Typhoid-ML-Diagnosis

A machine learning-based project to assist in the diagnosis of malaria and typhoid based on symptom analysis.

## Project Structure

```
Malaria-Typhoid-ML-Diagnosis/
├── data/
│   ├── raw/                # Original/raw datasets
│   └── processed/          # Cleaned/processed datasets
├── notebooks/              # Jupyter notebooks for each ML workflow stage
│   ├── 01_data_collection_and_exploration.ipynb
│   ├── 02_data_preprocessing_and_cleaning.ipynb
│   ├── 03_feature_selection_and_engineering.ipynb
│   ├── 04_model_training_and_evaluation.ipynb
│   └── 05_model_interpretation_and_reporting.ipynb
├── outputs/                # Final models, results, and figures
├── requirements.txt        # Python dependencies
├── README.md
├── .gitignore
└── venv/                   # Virtual environment (not tracked by git)
```

## Setup

1. Clone this repository.
2. Create and activate a Python virtual environment.
3. Install dependencies:
    ```
    pip install -r requirements.txt
    ```
4. Start working in the `notebooks/` directory.

## Workflow Overview

- **01_data_collection_and_exploration.ipynb:** Load and explore the dataset.
- **02_data_preprocessing_and_cleaning.ipynb:** Clean, encode, and balance data.
- **03_feature_selection_and_engineering.ipynb:** Select and engineer features.
- **04_model_training_and_evaluation.ipynb:** Train, tune, and evaluate models.
- **05_model_interpretation_and_reporting.ipynb:** Interpret model results and summarize findings.

## Recommended Python Libraries

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- imbalanced-learn
- shap
- lime
- jupyter

## License

MIT License
