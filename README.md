Employee Recruitment Analysis Project
This project analyzes an employee recruitment dataset to predict hiring decisions and uncover key factors influencing recruitment. It uses Python with libraries like Pandas, NumPy, Matplotlib, Seaborn, and Plotly for data processing, exploratory analysis, and visualizations including bar charts and pie charts.

Project Overview
The repository performs end-to-end data science on recruitment data, covering data loading, cleaning, EDA, and predictive modeling. Common features include age, gender, education level, and hiring decisions, helping HR optimize recruitment strategies.

Visualizations highlight distributions and relationships, such as hiring rates by demographics via bar and pie charts.
​

Key Features
Data preprocessing and handling missing values.

Exploratory Data Analysis (EDA) with statistical summaries.

Visualizations: Bar charts for categorical comparisons (e.g., hiring by gender/education), pie charts for proportions (e.g., hiring decision distribution).
​

Correlation analysis and predictive modeling for hiring outcomes.
​

Tech Stack
Languages: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Plotly (for interactive bar/pie charts), Scikit-learn (for ML predictions)

Environment: Jupyter Notebook


Why Random Forest is Used in This Project

In this project, Random Forest is used to predict whether a candidate will be selected or rejected during the recruitment process. The dataset contains several features such as age, gender, education level, experience, and interview score, which influence the final hiring decision.

Random Forest is a powerful algorithm in Machine Learning that builds multiple decision trees and combines their predictions to produce a more accurate and reliable result.


Project Output

The output of this project is a prediction of whether a candidate will be selected or rejected during the recruitment process based on the candidate’s details such as age, gender, education level, experience, and interview score.

The prediction model is built using Random Forest, a supervised learning algorithm from the field of Machine Learning.

Expected Output

After training the model, the system analyzes the candidate's information and produces one of the following outputs:

1 → Candidate Selected

0 → Candidate Rejected

Example:

Age	Education	Experience	Interview Score	Prediction
25	Bachelor's	2 Years	85	Selected
30	Master's	5 Years	78	Selected
22	Bachelor's	0 Years	60	Rejected
Model Performance

The model performance is evaluated using accuracy and confusion matrix.

Example output:

Model Accuracy: ~85–90% (depending on dataset)

Confusion Matrix: Shows correct and incorrect predictions of selected and rejected candidates.

Visual Outputs

The project also generates several graphs to better understand the data:

Bar chart for candidate distribution

Pie chart for selection rate

Feature importance graph showing which factors affect recruitment most

Final Result

The final result of the project is a machine learning model that can automatically predict recruitment decisions, helping organizations analyze candidate data and support the hiring process.
