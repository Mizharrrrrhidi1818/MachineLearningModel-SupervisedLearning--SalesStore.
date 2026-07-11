# 📊 Sales Forecasting Machine Learning Project

This project explores various supervised machine learning regression models to predict retail sales. The pipeline includes data preprocessing, outlier handling, feature engineering, and model evaluation.

## 📁 Dataset
The dataset used is the **Sales Forecasting** dataset available on [Kaggle](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting). 
It contains historical sales data including customer demographics, product categories, and shipping details.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook / Kaggle

## 📈 Models Evaluated
We trained and compared the following regression models:
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor
5. Support Vector Regression (SVR)
6. K-Nearest Neighbors (KNN)

## 🏆 Results
The models were evaluated using Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² Score.

| Model | MSE | MAE | R² Score |
| :--- | :--- | :--- | :--- |
| **Gradient Boosting** | **0.0543** | **0.1642** | **0.3030** |
| Random Forest | 0.0555 | 0.1622 | 0.2871 |
| Linear Regression | 0.0577 | 0.1675 | 0.2586 |
| Decision Tree | 0.0580 | 0.1679 | 0.2546 |
| SVM (RBF) | 0.0606 | 0.1720 | 0.2223 |
| KNN | 0.0847 | 0.2060 | -0.0883 |

**Winner:** Gradient Boosting Regressor achieved the highest R² score (0.3030), explaining ~30% of the variance in sales. 

*Note: The moderate R² score indicates that while the model captures some patterns, sales are highly influenced by external factors not present in the current feature set (e.g., seasonality, promotions).*

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/sales-forecasting-ml.git
