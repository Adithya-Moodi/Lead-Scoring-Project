 Lead Conversion Prediction for X Education

This repository contains the code, analysis, and documentation for a project aimed at building a logistic 
regression model to predict 'Hot Leads' for X Education. The objective is to improve lead conversion rates from 
30% to a target of 80%.

 Project Structure

o	`data/`: Contains the dataset used for this analysis.
o	`notebooks/`: Jupyter notebooks with detailed code and comments.
o	`docs/`: Documentation, including the Word file, presentation, and summary report.
o	`README.md`: This document.

 Files in the Repository

 Jupyter Notebook
o	Lead_Conversion_Prediction.ipynb: Detailed, commented notebook with the entire process of data 
preparation, exploratory data analysis (EDA), model building, and evaluation.

 Documentation
o	Solution_Document.pdf: Answers to the subjective questions posed by X Education.
o	Presentation.pdf: A concise presentation summarizing the analysis and findings.
o	Summary_Report.pdf: A brief summary report of the project.

 Installation
o	Clone the repository:
```sh
git clone https://github.com/your-username/lead-conversion-prediction.git
```
o	Navigate to the project directory:
```sh
cd lead-conversion-prediction
```
o	Install the required dependencies:
```sh
pip install -r requirements.txt
```



 Data Preparation

 Steps Followed:
o	Data Import and Libraries: Utilized pandas, numpy, matplotlib, seaborn, and scikit-learn for data 
analysis and modeling.
o	Missing Values: Handled missing values by:
o	Deleting columns with more than 40% missing data.
o	Dropping rows with less than 2% missing data.
o	Filling remaining missing values using median and mode for numerical and categorical data, 
respectively.
o	Duplicate Removal: Removed duplicate entries to ensure data integrity.
o	Outliers: Detected and removed outliers using the Interquartile Range (IQR) method.
o	Text Standardization: Standardized text data and converted relevant fields to binary values.
o	Dummy Variables: Created dummy variables for categorical features.
o	New Metrics: Derived new metrics like 'Time Per Visit'.

 Exploratory Data Analysis (EDA)

 Techniques Used:
o	Univariate Analysis: Histograms for variable distribution.
o	Bivariate Analysis: Scatter plots and box plots for relationship analysis.
o	Correlation Analysis: Correlation matrix heatmap.



 Model Building and Evaluation

 Model:
o	Logistic Regression: Built a logistic regression model with maximum iterations set to 1000.

 Evaluation Metrics:
o	Accuracy: 0.90
o	Precision: 0.91
o	Recall: 0.82
o	F1 Score: 0.87
o	ROC-AUC Score: 0.96



Model Interpretation

 Feature Importance:
Identified the top features contributing to lead conversion:
o	'Tags_Will revert after reading the email'
o	'Tags_Lost to EINS'
o	'Tags_Closed by Horizzon'
o	'City_Select'
o	'Lead Origin_Lead Add Form'

 Key Dummy Variables:
Highlighted impactful dummy variables:
o	'Last Activity_Olark Chat Conversation'
o	'Specialization_Select'
o	'Tags_Interested in other courses'
o	'What is your current occupation_Unemployed'
o	'Tags_Ringing'



 Recommendations

 Aggressive Conversion Strategy:
o	Prioritize high-probability leads.
o	Increase follow-up frequency and offer special promotions.
o	Train interns for efficient lead handling.

 Minimized Call Strategy:
o	Focus on leads with high conversion probability (>0.8).
o	Reduce follow-up calls, relying more on automated emails.
o	Reallocate resources to other tasks like lead nurturing and content creation.

 





Contact
For any questions or suggestions, please contact:
o	Name: Adithya Moodi
o	Email: adithya.moodi.m@gmail.com

