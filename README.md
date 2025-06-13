Wine Quality Prediction-Task5
 Objective
This project aims to predict wine quality (classified as good or bad) based on physicochemical properties using machine learning. The goal is to identify which features most influence wine quality and develop an accurate predictive model.

 Dataset
The WineQT dataset contains:
- 1,143 wine samples
- 11 physicochemical features (acidity, pH, alcohol content, etc.)
- Quality ratings (scale of 3-8)
- Converted to binary classification (quality ≥ 7 = good, else bad)

Steps Performed
 1. Data Preprocessing
- Removed duplicates and irrelevant columns
- Handled missing values (none found)
- Feature scaling using StandardScaler
- Feature selection using SelectKBest

 2. Exploratory Data Analysis
- Analyzed target variable distribution
- Examined feature correlations
- Visualized feature distributions and relationships
- Created pairplots for key features

 3. Machine Learning Modeling
- Implemented three classification models:
  - Random Forest
  - SGD Classifier
  - Support Vector Machine (SVM)
- Performed stratified train-test split (80-20)
- Conducted 5-fold cross-validation
- Evaluated using accuracy, precision, recall, F1-score

 4. Results & Interpretation
- Feature importance analysis
- Model performance comparison
- Best model selection


 Tools & Technologies
- Python 
- Libraries:
  - Pandas, NumPy 
  - Matplotlib, Seaborn 
  - Scikit-learn 
- Jupyter Notebook 

Key Findings
1. Important Features: Alcohol content and volatile acidity are most predictive of quality
2. Class Imbalance: Fewer high-quality wines (quality ≥ 7) in dataset
3. Best Model: Random Forest achieved highest accuracy (89.5%)
4. Feature Impact: Higher alcohol content correlates with better quality


