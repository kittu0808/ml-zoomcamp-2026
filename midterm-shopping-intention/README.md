# Online Shoppers Purchasing Intention Prediction

## Project Overview
This project predicts whether an online shopping session will result in a purchase.

## Dataset
The project uses the Online Shoppers Purchasing Intention Dataset from the UCI Machine Learning Repository.

Dataset source: https://archive.ics.uci.edu/dataset/468/online

- Original records: 12,330
- Features: 17
- Target variable: Revenue
- Target classes: Purchase (True) and No Purchase (False)

## Project Workflow
1. Data loading and inspection
2. Exploratory Data Analysis
3. Data cleaning and preprocessing
4. Train-test splitting
5. Model training
6. Model evaluation
7. Threshold tuning
8. Feature importance analysis
9. Model saving

## Models
- Logistic Regression
- Random Forest Classifier

The Random Forest model with a decision threshold of 0.30 achieved the following test results:

| Metric | Score |
|---|---:|
| Accuracy | 0.7120 |
| Precision | 0.3127 |
| Recall | 0.7016 |
| F1-Score | 0.4326 |
| ROC-AUC | 0.7851 |

## Repository Structure
- `data/` - Dataset
- `models/` - Saved machine learning model
- `notebooks/` - Notebook folder
- `shopping_intention_analysis.ipynb` - Project notebook

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

## How to Run
1. Clone this repository.
2. Install the required dependencies.
3. Open `shopping_intention_analysis.ipynb` in Jupyter Notebook.
4. Run the notebook cells sequentially.

## Limitations and Future Improvements
- Improve purchase prediction precision.
- Explore additional classification algorithms.
- Perform hyperparameter tuning.
- Evaluate additional decision thresholds.
- Monitor model performance over time.

## Author
Shubham Anant Kulkarni.
