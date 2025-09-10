# Car Price Prediction

A comprehensive machine learning project that predicts used car prices based on various vehicle characteristics. This project demonstrates advanced data preprocessing techniques, feature engineering, and statistical analysis to build an accurate car price prediction model.

## 🎯 Project Overview

This project analyzes a dataset of 1,642 used cars to predict their market prices using machine learning techniques. The model considers multiple factors including car specifications, condition, age, and usage patterns to provide accurate price estimates.

## ✨ Key Features

- **Advanced Data Preprocessing**: Comprehensive data cleaning and transformation pipeline
- **Smart Feature Engineering**: 
  - Car age calculation from manufacturing year
  - Distance standardization (miles to kilometers conversion)
  - Intelligent categorical encoding
- **Statistical Analysis**: Correlation matrix analysis for feature importance
- **Robust Encoding**: 
  - One-hot encoding for nominal variables (model, motor type, wheel, color, type)
  - Ordinal encoding for car condition status
- **Feature Standardization**: StandardScaler implementation for optimal model performance

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Scikit-learn** - Machine learning utilities and preprocessing
- **Matplotlib/Seaborn** - Data visualization
- **Jupyter Notebook** - Interactive development environment

## 📊 Dataset Information

The dataset contains **1,642 car records** with the following features:

| Feature | Description |
|---------|-------------|
| Model | Car model/brand |
| Year | Manufacturing year |
| Motor Type | Engine type specification |
| Running Distance | Total kilometers driven |
| Wheel | Wheel configuration |
| Color | Vehicle color |
| Type | Vehicle category |
| Status | Car condition (new, excellent, good, etc.) |
| Motor Volume | Engine displacement |
| **Price** | Target variable - market price |

## 🚀 Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/Zyttik-m/Car_price_prediction.git
cd Car_price_prediction
```

2. **Install required dependencies**
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

3. **Launch Jupyter Notebook**
```bash
jupyter notebook car_predic.ipynb
```

## 💻 Usage

1. Open the `car_predic.ipynb` notebook
2. Run all cells sequentially to reproduce the analysis
3. The notebook includes:
   - Data loading and exploration
   - Comprehensive preprocessing pipeline
   - Feature engineering transformations
   - Correlation analysis
   - Model preparation steps

## 🔧 Data Preprocessing Pipeline

### 1. Feature Engineering
- **Age Calculation**: Convert manufacturing year to car age
- **Distance Standardization**: Normalize running distance measurements
- **Status Encoding**: Map car conditions to numerical values

### 2. Categorical Encoding
- **One-Hot Encoding**: Applied to nominal variables (model, motor type, wheel, color, type)
- **Ordinal Encoding**: Applied to car status for preserving condition hierarchy

### 3. Feature Scaling
- **StandardScaler**: Normalize numerical features for optimal model performance

### 4. Statistical Analysis
- **Correlation Matrix**: Identify relationships between features and target price
- **Feature Importance**: Determine most influential factors in price prediction

## 📁 Project Structure

```
Car_price_prediction/
├── car_predic.ipynb          # Main analysis notebook
├── submission.csv            # Processed dataset/predictions
├── data/                     # Raw data directory
│   └── [dataset files]
└── README.md                 # Project documentation
```

## 📈 Key Insights

- Car condition (status) significantly impacts pricing
- Vehicle age shows strong correlation with depreciation
- Motor specifications and type influence market value
- Comprehensive preprocessing improves model reliability

## 🔮 Future Improvements

- [ ] Implement multiple regression algorithms (Random Forest, XGBoost, Neural Networks)
- [ ] Add hyperparameter tuning with GridSearchCV
- [ ] Implement cross-validation for robust model evaluation
- [ ] Create interactive price prediction web application
- [ ] Add advanced visualizations for insights presentation
- [ ] Include model performance metrics and comparison


## 👨‍💻 Author

**Kittithat Chalermvisutkul**
- GitHub: [@Zyttik-m](https://github.com/Zyttik-m)


