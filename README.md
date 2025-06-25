# Exploratory-data-analysis-

Navigation Menu
AI-ML-internship-task2

Code
Issues
Pull requests
Exploratory Data Analysis for AI/ML Internship Task 2

License
 MIT license
 0 stars
 0 forks
 0 watching
 1 Branch
 0 Tags
 Activity
Public repository
devaraj077/AI-ML-internship-task2
Name	
devaraj077
devaraj077
12 minutes ago
titanic_2
12 minutes ago
.DS_Store
12 minutes ago
.gitattributes
1 hour ago
.gitignore
1 hour ago
LICENSE
1 hour ago
README.md
12 minutes ago
Titanic-Dataset.csv
12 minutes ago
titanictask_2.py
12 minutes ago
Repository files navigation
README
MIT license
AI/ML Internship – Task 2: Exploratory Data Analysis (EDA)
🎯 Objective
The goal of this task is to perform Exploratory Data Analysis (EDA) to understand patterns, trends, and relationships in the dataset using descriptive statistics and visualizations.

This helps prepare the data for further machine learning modeling by identifying:

Missing values
Outliers
Feature correlations
Skewness
Relationships between variables (e.g., survival vs gender/class)
🧰 Tools & Libraries Used
Tool	Purpose
Python	Main programming language used
Pandas	For loading and summarizing data
NumPy	For numerical operations
Matplotlib / Seaborn	For creating visualizations
Jupyter Notebook / Google Colab	For interactive coding and analysis
📁 Dataset Used
We used the Titanic Dataset, which contains information about passengers aboard the RMS Titanic.

🔗 Download Dataset
📋 Key Features:
PassengerId
Survived
Pclass
Name
Sex
Age
SibSp
Parch
Ticket
Fare
Cabin
Embarked
📊 Steps Performed
Loaded the dataset using Pandas.
Generated summary statistics (mean, median, std, etc.) to understand feature distributions.
Created histograms for numeric features to detect skewness.
Used boxplots to visualize outliers in features like Fare and Age.
Built a correlation heatmap to identify relationships between numerical features.
Plotted pairplots to study interactions between multiple variables.
Identified patterns such as:
Most passengers paid low fares
Survival rate varied significantly by gender and class
Made basic inferences from visuals to guide future preprocessing and modeling steps.
📸 Visualizations
All visualizations were saved in the eda_plots/ folder.

🖼️ Included Visualizations:
Visualization	Description
Histograms	Show distribution of each numeric feature
Boxplots	Detect outliers in fare, age, etc.
Correlation Heatmap	Understand how numerical features relate to each other
Pairplot	View pairwise relationships between all numerical features
Survival Count Plot	See how many passengers survived vs died
Barplots	Compare survival rates across categories like gender or passenger class
📝 Interview Questions Answered
Here are short answers to the EDA-related interview questions listed in the task description:

1. What is the purpose of EDA?
EDA helps us understand the structure, patterns, and issues in the data before building models. It guides decisions on cleaning, transformation, and feature selection.

2. How do boxplots help in understanding a dataset?
Boxplots show central tendency, spread, and outliers in numerical data — helping identify extreme values and skewed distributions.

3. What is correlation and why is it useful?
Correlation measures the strength and direction of the relationship between two variables. It's useful for feature selection and detecting multicollinearity.

4. How do you detect skewness in data?
Skewness can be detected using histograms or calculated directly using df.skew(). A right-skewed distribution has a long tail on the right side.

5. What is multicollinearity?
Multicollinearity occurs when input features are highly correlated with each other, which can reduce model performance and interpretability.

6. What tools do you use for EDA?
We used Python libraries like Pandas for data handling, Matplotlib and Seaborn for visualization, and Jupyter Notebook / Google Colab for execution.

7. Can you explain a time when EDA helped you find a problem?
During EDA, we found that the Fare column had many high-value outliers. This led to scaling or removing those values to prevent bias in modeling.

8. What is the role of visualization in ML?
Visualization helps understand data behavior, detect anomalies, and communicate findings clearly. It plays a key role in feature engineering and model interpretation.

📦 Files Included in This Repository
File	Description
titanic_eda.ipynb	Jupyter notebook containing full EDA process
titanic.csv	Original dataset used
README.md	This file – explains what was done
eda_plots/	Folder containing saved visualizations
eda_analysis.py (optional)	Python script version of the EDA code
🚀 How to Run the Code
Option 1: Using Google Colab
Open the notebook: titanic_eda.ipynb
Upload the titanic.csv file when prompted
Run all cells to regenerate plots and stats
Option 2: Local Machine
Install required packages:
pip install pandas numpy matplotlib seaborn
