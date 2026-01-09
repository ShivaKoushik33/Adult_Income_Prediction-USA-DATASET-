# Adult Income Prediction

This project aims to predict whether an individual's income exceeds $50K/yr based on census data. It uses various machine learning models to analyze demographic and employment information.

## Dataset

The project uses the `adult.csv` dataset, which includes the following features:
- `age`: Age of the individual.
- `workclass`: Employment status (e.g., Private, Self-emp-not-inc, Local-gov).
- `fnlwgt`: Final weight.
- `education`: Highest level of education achieved.
- `education.num`: Numerical representation of education level.
- `marital.status`: Marital status.
- `occupation`: Type of occupation.
- `relationship`: Relationship status.
- `race`: Race.
- `sex`: Gender.
- `capital.gain`: Capital gains.
- `capital.loss`: Capital losses.
- `hours.per.week`: Hours worked per week.
- `native.country`: Country of origin.
- `income`: Target variable (<=50K or >50K).

## Technologies Used

- **Python**: Primary programming language.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical operations.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning models and evaluation metrics.
- **XGBoost**: Gradient boosting framework.

## Models Implemented

The following models are trained and evaluated in the notebook:
1.  **Logistic Regression**
2.  **Decision Tree Classifier**
3.  **Random Forest Classifier**
4.  **XGBoost Classifier**
5.  **Voting Classifier** (Ensemble of the above models)

## Usage

1.  Ensure you have the required libraries installed:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn xgboost
    ```
2.  Place the `adult.csv` file in the same directory as the notebook.
3.  Open `adult-income-prediction-with-lr-dt-rf-xgb-vc.ipynb` in Jupyter Notebook or JupyterLab.
4.  Run the cells sequentially to load data, preprocess it, train models, and view results.

## Results

The notebook includes evaluation metrics such as accuracy, precision, recall, and F1-score for each model, along with confusion matrices and classification reports.
