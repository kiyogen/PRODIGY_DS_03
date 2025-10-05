# PRODIGY_DS_03

## Task 3: Decision Tree Classifier on Bank Marketing Dataset

This task is part of my Prodigy Infotech internship.  
The objective was to build a **Decision Tree classifier** to predict whether a customer will subscribe to a product or service based on demographic and behavioral data.

### Dataset
- **Bank Marketing Dataset** from UCI Machine Learning Repository  
- Full dataset used (`bank-full.csv`)   

### Contents
- `Task3.ipynb` → Code for loading dataset, training Decision Tree, and evaluating the model  
- Output → Accuracy metrics, confusion matrix, classification report, and feature importance plot  

### Approach
1. **Data Loading**: Dataset imported directly from UCI using `ucimlrepo`.  
2. **Encoding**: Categorical variables and target variable encoded to numeric using `LabelEncoder`.  
3. **Train/Test Split**: 80% train, 20% test.  
4. **Decision Tree Model**:  
   - Trained on all features.  
   - Default parameters used (no max depth set)  
5. **Evaluation**:  
   - Accuracy  
   - Confusion matrix  
   - Classification report  
6. **Feature Importance**: Bar chart of top features (optional, included in notebook).  

### Notes  
- Tree visualization skipped due to large dataset size (45,211 rows). 

