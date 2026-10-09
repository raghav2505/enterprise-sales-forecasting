# Enterprise Sales Forecasting Pipeline

## Project Overview
This project uses machine learning to forecast retail sales using historical sales data. It compares Decision Tree, Random Forest, and XGBoost regression models to identify the best-performing model.

## Objectives
- Analyze historical retail sales data.
- Create time-based features and sales lag features.
- Train and compare multiple machine learning models.
- Evaluate predictions using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
- Save and reload the trained model for future predictions.

## Dataset
Dataset: Store Sales - Time Series Forecasting  
Source: Kaggle  
Link: https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data

The dataset contains daily sales records across stores and product families.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Jupyter Notebook
- Pickle

## Machine Learning Models
1. Decision Tree Regressor
2. Random Forest Regressor
3. XGBoost Regressor

## Preliminary Results
| Model | MAE | RMSE |
|---|---:|---:|
| Random Forest | 95.46 | 379.09 |
| XGBoost | 101.56 | 399.56 |
| Decision Tree | 129.08 | 586.69 |

Random Forest performed best among the three models in the current experiment.

**Note:** These are preliminary validation results from sampled training and validation rows. They should not be interpreted as final production performance.

## Project Structure
```
enterprise-sales-forecasting/
├── Enterprise_Sales_Forecasting.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run
1. Clone or download this repository.
2. Install the required Python packages.
3. Download the dataset from Kaggle and place the CSV files in the expected local data folder.
4. Open the notebook in Jupyter Notebook.
5. Run the cells in order.

## Future Improvements
- Improve forecasting with additional store, holiday, oil price, and transaction features.
- Perform more robust chronological validation.
- Tune model hyperparameters.
- Build an interactive sales forecasting dashboard.

## Author
Data Science Graduate | Machine Learning Enthusiast
