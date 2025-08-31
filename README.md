# Classification - Obesity Levels

A machine learning project for classifying obesity levels based on eating habits and physical condition using multiple algorithms and comprehensive data analysis.

## 📊 Dataset Overview

The dataset contains information about individuals' eating habits, physical condition, and lifestyle factors to predict obesity levels. It includes both real and synthetic data with 2,111 records and 17 features.

### Key Features:
- **Gender**: Biological gender (Male/Female)
- **Age**: Age of the individual (14-61 years)
- **Height**: Height in meters (1.45-1.98m)
- **Weight**: Weight in kg (39-173kg)
- **Family History**: Family history of overweight (yes/no)
- **FAVC**: Frequent consumption of high caloric food (yes/no)
- **FCVC**: Frequency of vegetable consumption (1-3)
- **NCP**: Number of main meals (1-4)
- **CAEC**: Consumption of food between meals (no/Sometimes/Frequently/Always)
- **SMOKE**: Smoking habit (yes/no)
- **CH2O**: Daily water consumption (1-3 liters)
- **SCC**: Calories consumption monitoring (yes/no)
- **FAF**: Physical activity frequency (0-3)
- **TUE**: Time using technology devices (0-2 hours)
- **CALC**: Alcohol consumption (no/Sometimes/Frequently/Always)
- **MTRANS**: Transportation used (Walking/Bike/Motorbike/Public_Transportation/Automobile)

### Target Variable:
**NObeyesdad**: Obesity level with 7 categories:
- Insufficient_Weight
- Normal_Weight
- Overweight_Level_I
- Overweight_Level_II
- Obesity_Type_I
- Obesity_Type_II
- Obesity_Type_III

## 🔧 Data Preprocessing

1. **Data Cleaning**: 
   - Removed 24 duplicate records
   - No missing values found
   - Final dataset: 2,087 records

2. **Outlier Detection**: 
   - Used boxplots to identify outliers in numerical features
   - Applied appropriate handling techniques

3. **Feature Engineering**:
   - Label encoding for binary categorical variables
   - One-hot encoding for multi-category variables
   - Standard scaling for numerical features

## 🤖 Machine Learning Models

The project implements multiple classification algorithms:

1. **Logistic Regression**
2. **Support Vector Machine (SVM)**
3. **K-Nearest Neighbors (KNN)**
4. **Decision Tree**
5. **Random Forest**
6. **XGBoost**
7. **Neural Network (MLP)**
8. **Deep Learning (TensorFlow/Keras)**

## 📈 Model Evaluation

Models are evaluated using:
- Accuracy Score
- Precision, Recall, F1-Score
- Confusion Matrix
- Classification Report

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost tensorflow
```

### Running the Project
1. Clone the repository
2. Install required dependencies
3. Run the Jupyter notebook:
   ```bash
   jupyter notebook "Classification_Estimation_of_Obesity_Levels_Based_On_Eating_Habits_and_Physical_Condition.ipynb"
   ```

## 📁 Project Structure
```
Classification-Obesitylevels/
├── Classification_Estimation_of_Obesity_Levels_Based_On_Eating_Habits_and_Physical_Condition.ipynb
├── Classification-Estimation of Obesity Levels Based On Eating Habits and Physical Condition.ipynb
├── README.md
```

## 📊 Results

The project achieves high accuracy in classifying obesity levels, with ensemble methods and neural networks showing particularly strong performance. Detailed results and model comparisons are available in the notebook.

## 🔍 Key Insights

- Family history and eating habits are strong predictors of obesity levels
- Physical activity frequency shows significant correlation with obesity classification
- Age and gender play important roles in obesity prediction
- Transportation mode correlates with physical activity levels


## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.