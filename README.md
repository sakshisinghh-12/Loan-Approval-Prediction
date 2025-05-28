# Loan-Approval-Prediction

# Project Overview
This project aims to predict whether a loan application will be approved based on historical data. By applying data cleaning, exploratory data analysis (EDA), feature engineering, and classification models, we derive insights and build a predictive system to assist financial institutions in making faster and data-driven decisions.

# Tools & Technologies
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Techniques**: Data Cleaning, EDA, Feature Engineering, Classification Modeling

# Key Steps
1. **Data Preprocessing:**  
   - Handled missing values using statistical imputation.
   - Identified and treated outliers using visual inspection (box plots).
   - Applied log transformation to normalize skewed data distributions.

2. **Exploratory Data Analysis (EDA):**  
   - Visualized relationships between loan status and categorical features (e.g., Gender, Education, Marital Status).
   - Generated correlation heatmaps to identify highly influential features.

3. **Feature Engineering:**  
   - Created new features such as `Total_Income` and transformed variables to improve model performance.

4. **Modeling:**  
   - Trained and compared models including Logistic Regression, Decision Tree, and Random Forest.
   - Evaluated model performance using accuracy and cross-validation scores.

# Results
- **Random Forest Classifier** performed the best with the highest accuracy.
- **Credit History**, **Total Income**, and **Loan Amount** were identified as top features influencing approval decisions.

# Business Recommendation
Financial institutions can streamline the approval process by prioritizing credit history and applicant income as early screening indicators. The model can serve as a baseline for automating parts of the loan approval pipeline.
