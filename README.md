#🧠 Brain Stroke Analysis & Prediction
This project aims to analyze and predict brain strokes using machine learning techniques. Brain strokes are life-threatening medical emergencies, and early prediction can be life-saving. By analyzing patient data — such as age, gender, glucose levels, and lifestyle — we can identify patterns that contribute to stroke risk and implement early preventive measures.

Dataset Description
The dataset includes the following features:

Feature	Description
Age	              Age of the patient (years)
Gender	          Male or Female
Hypertension	    1 = Yes, 0 = No
Heart Disease	    1 = Yes, 0 = No
Ever Married	    Yes or No
Work Type	        Private, Self-employed, or Govt_job
Residence Type  	Rural or Urban
Avg Glucose Level	Average glucose level (mmol/L)
BMI	              (kg/m²)
Smoking Status	  Smokes, Never smoked, Formerly smoked, etc.
Stroke	1 = Stroke occurred, 0 = No stroke

🔍 Exploratory Data Analysis (EDA)
The following visualizations were used to explore the dataset:

Bar Plot: Category-wise comparisons

Pair Plot: Relationships between features

Histogram: Distribution of continuous variables

Boxplot: Outlier detection and spread

Heatmap: Correlation matrix

🤖 Machine Learning Models Used
Four ML models were trained to predict whether a person is at risk of a stroke:

Algorithm	Accuracy
Logistic Regression	94%
Decision Tree	90%
Random Forest	94%
K-Nearest Neighbors	94%

All models were trained after appropriate preprocessing and scaling of the dataset.

✅ Conclusion
The machine learning models — particularly Logistic Regression, Random Forest, and K-Nearest — showed promising performance with high accuracy (94%). This suggests that ML can be a powerful tool in identifying individuals at risk of brain stroke and enabling early intervention.

