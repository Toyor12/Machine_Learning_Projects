# Machine Learning Projects

A collection of end-to-end machine learning projects built in Python using Jupyter Notebooks, covering regression modelling, feature engineering, data preprocessing, and model evaluation.

---

## Projects

### FIFA 21 Player Value Prediction

**Objective:** Predict the market value of FIFA 21 players using player attributes, performance ratings, and positional data — framed as a supervised regression problem.

**Business context:** Player valuation is a high-stakes decision in football analytics. Accurate value prediction supports transfer budget planning, contract negotiation, and squad optimisation — directly analogous to demand forecasting and resource allocation problems in commercial data science.

**Approach:**
- Exploratory data analysis (EDA) to understand feature distributions, correlations, and outliers across 18,000+ player records
- Data cleaning and preprocessing: handling missing values, encoding categorical variables (nationality, club, position), and scaling numerical features
- Feature engineering: derived attributes from raw FIFA ratings to improve signal quality
- Model training and comparison across multiple regression algorithms (Linear Regression, Random Forest, Gradient Boosting)
- Hyperparameter tuning and cross-validation to optimise generalisation performance
- Model evaluation using RMSE, MAE, and R² metrics with visualised residual analysis

**Stack:** Python · pandas · NumPy · scikit-learn · matplotlib · seaborn · Jupyter Notebook

**Key outcome:** Developed a regression model that accurately estimates player market value from in-game attributes, demonstrating end-to-end ML workflow from raw data to evaluated, interpretable predictions.

---

## Skills Demonstrated

- Supervised machine learning (regression)
- Feature engineering and selection
- Data preprocessing pipelines
- Model evaluation and comparison
- Exploratory data analysis and visualisation
- Python-based ML workflow (scikit-learn, pandas, matplotlib)

---

## How to Run

```bash
# Clone the repository
git clone https://github.com/Toyor12/Machine_Learning_Projects.git
cd Machine_Learning_Projects

# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

# Launch the notebook
jupyter notebook "FIFA 21 PLAYER VALUE PREDICTION.ipynb"
```

---

## Author

**Oyewole Oluwatoyosi** — Data Scientist | Python · ML · Azure · BigQuery  
[LinkedIn](https://linkedin.com/in/toyosiwole) · [GitHub](https://github.com/Toyor12)
