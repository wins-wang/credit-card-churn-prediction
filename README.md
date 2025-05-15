# Credit Card Churn Prediction with GridMaster

This project is a comprehensive machine learning pipeline for predicting customer churn in a credit card dataset. It showcases the full lifecycle from data cleaning and exploratory analysis to advanced model development using **GridMaster**, a custom-built Python package designed to optimize and compare multiple machine learning models efficiently.

🌐 [View Project Page](https://winston-wang.com/portfolio/credit-card-churn)

## 📁 Project Structure
```
credit-card-churn-prediction/
├── data/                     # Input datasets
├── notebooks/                # Jupyter Notebooks
│   ├── 01_data_cleaning.ipynb
│   ├── 02_analysis.ipynb
│   └── 03_modeling_with_gridmaster.ipynb
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt
```

## 📊 Notebooks Overview
- **01_data_cleaning.ipynb** → Loads and cleans the raw dataset, transforms key variables.
- **02_analysis.ipynb** → Performs exploratory data analysis (EDA), generates insights and visualizations.
- **03_modeling_with_gridmaster.ipynb** → Builds and optimizes models using **GridMaster**, including:
  - Multi-model, multi-stage coarse-to-fine hyperparameter tuning
  - Advanced visualizations of tuning curves, performance metrics, and feature importance
  - Extraction of best models and parameters for deployment
  - Summary analysis comparing classifiers (Logistic Regression, Random Forest, XGBoost) based on recall
  - Demonstration of both new-user Quickstart case and advanced use cases for GridMaster


## 🚀 Key Features
- Multi-model coordination: Logistic Regression, Random Forest, XGBoost, catboost,LightGBM
- Coarse-to-fine hyperparameter tuning
- High-performance recall-focused optimization
- Visual tuning diagnostics and feature importance plots
- Best model selection and summary analysis

## 💡 Quickstart
1. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
2. Run notebooks in order (01 → 02 → 03) to reproduce the full analysis.
3. For **GridMaster** usage, refer to the **[official user manual](https://gridmaster.readthedocs.io/en/main/)**.

## 📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

---

✨ **Author:** Winston Wang  
🔗 [Personal Website](https://winston-wang.com) | [GitHub](https://github.com/wins-wang)
