# Continuous Glucose Monitoring (CGM) Analysis and Prediction

This project focuses on the analysis and prediction of Continuous Glucose Monitoring (CGM) data using machine learning techniques. The dataset contains glucose level data along with carbohydrate intake (CHO), insulin administration, and calculated risk factors.

## Features
### Data Preprocessing
- Loading CSV files from Google Drive.  
- Combining data from multiple subjects (adolescents, adults, and children).  
- Handling missing values.  
- Calculating moving averages for CGM, insulin, and CHO.  

### Data Visualization
- Histograms for CGM values by subject type.  
- Pie charts for average insulin usage.  
- Strip plots to visualize CHO distribution.  
- Line plots to show CGM, CHO, and insulin trends over time.  

### Feature Engineering
- Correlation matrix generation.  
- Statistical analysis using descriptive statistics.  

### Machine Learning Modeling
- Applied Support Vector Machine (SVM) with K-Fold cross-validation.  
- Synthetic Minority Over-sampling Technique (SMOTE) for class imbalance handling.  
- Performance evaluation using accuracy, precision, recall, and F1 score.  

### Model Evaluation
- ROC curve visualization.  
- Confusion matrix analysis for hypoglycemia and hyperglycemia.  
- Learning curve generation to analyze model behavior.  

## Installation
1. Clone the repository:
    ```bash
    https://github.com/Qasim-Shah-73/Diabetes-Detection.git
    ```
2. Install dependencies using pip:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the notebook using Google Colab or Jupyter Notebook.

## Requirements
- Python 3.8+  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly  
- Scikit-Learn  
- Imbalanced-Learn  
- TensorFlow  
- Keras  

## Results
The project evaluates the performance of SVM models, compares accuracy metrics, and visualizes class distributions. Key insights into glucose trends and risk factor correlations are highlighted using descriptive statistics and visualizations.

