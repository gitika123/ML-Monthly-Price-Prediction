# Monthly Price Prediction using Machine Learning

A machine learning project that predicts monthly prices using multiple regression algorithms including Linear Regression, Random Forest Regression, and Decision Tree Regression. The project includes a web-based frontend built with Node-RED for interactive price predictions.

![Project Demo](https://user-images.githubusercontent.com/49466550/59993345-9e1fda00-966d-11e9-88d5-1adc7975aecf.PNG)

## 📋 Overview

This project leverages machine learning techniques to predict monthly prices based on temporal features (Month, Year, Date). The implementation compares multiple regression algorithms to find the best model for price prediction.

## ✨ Features

- **Multiple ML Models**: Implements Linear Regression, Random Forest Regression, and Decision Tree Regression
- **Data Preprocessing**: Includes feature scaling and standardization for optimal model performance
- **Interactive Frontend**: Node-RED based web interface for easy price predictions
- **Model Evaluation**: Uses R² score, Mean Squared Error (MSE), and Mean Absolute Error (MAE) metrics
- **Data Visualization**: Includes scatter plots and visualizations for data exploration

## 🛠️ Technologies Used

- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Scikit-learn**: Machine learning algorithms and evaluation metrics
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization
- **Node-RED**: Frontend interface for predictions

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Monthly_price_prediction.git
cd Monthly_price_prediction
```

2. Install required Python packages:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

3. Ensure you have Node-RED installed (for frontend):
```bash
npm install -g node-red
```

## 🚀 Usage

1. **Prepare your data**: 
   - Place your CSV file with columns: `Month`, `Year`, `Date`, and `Price`
   - Update the file path in the notebook

2. **Run the Jupyter Notebook**:
   - Open `Monthly price prediction4 (1)-checkpoint.ipynb`
   - Execute all cells to train the models and generate predictions

3. **Start Node-RED** (if using the frontend):
```bash
node-red
```

## 📊 Models Implemented

1. **Linear Regression**: Baseline regression model
2. **Random Forest Regression**: Ensemble method with multiple decision trees
3. **Decision Tree Regression**: Non-linear regression model

## 📈 Results

The models are evaluated using:
- **R² Score**: Coefficient of determination
- **Mean Squared Error (MSE)**: Average squared differences
- **Mean Absolute Error (MAE)**: Average absolute differences


