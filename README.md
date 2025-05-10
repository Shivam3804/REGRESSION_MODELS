# 🏠 Ames Housing Regression Project

This project explores and compares different regression models to predict house prices using the Ames Housing dataset. It aims to evaluate how well each model performs and understand which one gives the most accurate predictions.

## Dataset

- **Name**: Ames Housing Dataset
- **Source**: [Kaggle](https://www.kaggle.com/datasets/prevek18/ames-housing-dataset)
- **Target**: `SalePrice`
- **Features**: 80 housing features including area, neighborhood, quality, etc.

## Workflow

1. **Data Preprocessing**
   - Handling missing values
   - Label encoding and feature scaling
   - Saving cleaned dataset

2. **Model Training**
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - Neural Network Regressor (in-built model using sklearn)
   - Neural Network (from scratch using tensorflow)

3. **Evaluation**
   - Metrics: MSE, R² Score
   - Visual comparison of predictions
   
## Results

| Model                  | MSE (lower is better) | R² Score (higher is better)  |
|------------------------|----------------------:|-----------------------------:|
| Linear Regression      | 1,181,493,833         | 0.85                         |
| Decision Tree Regressor| 1,321,089,173         | 0.83                         |
| Random Forest Regressor| 695,616,715           | 0.91                         |
| Neural Network(inbuilt)| 1,116,480,820         | 0.86                         |
| Neural Network(scratch)| 1,665,063,936         | 0.87                         |

> ✅ Random Forest gave the best overall performance on this dataset.

## Visualization

Graphs comparing predicted vs actual prices are included in the `plots/` folder.

## Technologies

- Python
- Jupyter Notebook
- Scikit-learn
- Matplotlib
- Pandas
- Tensorflow
