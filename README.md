# Predicting Arsenic and Manganese Contamination in Private Well Water with Machine Learning: An Integrated Analysis of Geological, Construction, and Permitting Data

This code was generated to support the manuscript entitled  'Predicting Arsenic and Manganese Contamination in Private Well Water with Machine Learning: An Integrated Analysis of Geological, Construction, and Permitting Data' soon to be published.

<p align="center">
<img src = 'https://github.com/user-attachments/assets/fa67bfbe-597e-4f3b-bb76-4509c225d1de' width = '600'>
</p>

<br>
These analyses were used to determine if geology, geography, and well construction characteristics can predict metal (arsenic and manganese) contamination and what at what thresholds are certain wells more at risk for contamination. All analyses in this respository are designated by their figure number or table number in the manuscript in parantheses.

> In the instance that the files are unable to rendered, they can be rendered at the [NBViewer link](https://nbviewer.org/github/UNCSRP/Predicting-Arsenic-and-Manganese-Contamination-in-Private-Well-Water-with-Machine-Learning-An/tree/main/). 

# 1. Data Imputation
- Using random forest to impute the predictor variables and Quantile Regression Imputation of Left-Censored Data (QRILC) to impute each metal's concentration

# 2. iAs/Mn Contamination Mapping (Figure 1)
- Visualizing iAs/Mn contamination by census tract in Union County, NC

# 3. Metal Prediction (Table 3)
- Predicting arsenic and manganese contamination based on well data using supervised ML (random forest and support vector machine (SVM))

# 4. ML Visualizations (Figures 2-4)
- Confusion Matrix Figure (Figure 2)
  - Visualization of confusion matrix metrics from the top performing supervised machine learning model across the use cases (SVM with a linear kernel)
- Variable Importance Plot (Figure 3)
  - Shows importance of each predictor from the top performing machine learning (ML) models (SVM with a linear kernel) for use case 1
- Decision Boundary Plot (Figure 4)
  - Visualization of two predictors to determine how well those variables could predict metal contamination
