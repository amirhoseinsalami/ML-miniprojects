# Housing Price Prediction

Predicting California housing prices using regression models and feature analysis.

## Libraries Used
- `NumPy` — numerical operations
- `Pandas` — data manipulation
- `Scikit-learn` — model training and evaluation
- `Matplotlib` / `Seaborn` — data visualization

## Models Used
- **Linear Regression** — baseline model
- **Random Forest Regressor** — improved accuracy with ensemble learning

## Features
- Data preprocessing and feature engineering
- Model training and comparison
- Feature importance analysis
- Evaluation with RMSE and R² score

## Dataset
California Housing dataset from `sklearn.datasets`.  
Contains 20,640 samples with features like median income, house age, location, etc.

## How to Run
1. Clone the repository:
```bash
   git clone https://github.com/YOUR_USERNAME/housing-price-prediction
```   
   

2. Install dependencies:
```bash
   pip install numpy pandas scikit-learn matplotlib seaborn
```

3. Run the notebook:
```bash
   jupyter notebook housing_price_prediction.ipynb
```

## Results
Model 	            RMSE 	    R² Score
Linear Regression 	~68,000 	~0.64
Random Forest 	    ~59,000 	~0.72
Random Forest outperformed Linear Regression, with median income identified as the most important feature.
