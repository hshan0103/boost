# X_hosp_bill_estimation
Hospital X is seeking for the data solution for patients bills estimation. Working on POc for the usecase. 

# Data Pipelines
- Data sourced.
- Data preprocessing 
- Model training. 

# Data Preprocessing Notes
Applying Bert to construct matrix for text and then build clustering model for features synthesis to make the clinical histories and diagnosis data applicable for regression modeling.

# Outcome
- Around 70% prediction is within +/- x% of true_y. 
- x is the given threshold by hospital. 
- Due to limited data, in term of features available, this is not an ideal model with the current performance. 
