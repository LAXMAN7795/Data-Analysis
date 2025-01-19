**Student Data Analysis:**
This repository contains a Jupyter Notebook that analyzes student performance data to uncover insights about the factors affecting their academic scores. The analysis uses Python libraries like pandas, numpy, matplotlib, and seaborn to process and visualize the data.

**Dataset Overview:**
The dataset, Expanded_data_with_more_features.csv, contains detailed information about students, including:

Demographics: Gender, ethnic group.
Parental Background: Education level and marital status.
Test Preparation: Whether students completed test preparation.
Academic Scores: Scores in Math, Reading, and Writing.

**Analysis Highlights**
1. Data Cleaning
Removed unnecessary columns (e.g., Unnamed: 0).
Standardized entries in the TestPrep column by replacing "none" with "NotPrepared."
2. Key Insights
Gender Distribution
Visualized with a bar chart, showing that the dataset includes more females than males.
Parental Education Impact
Heatmap analysis reveals a strong positive correlation between parents' education levels and students' academic scores.
Parental Marital Status
Analysis indicates minimal or negligible impact of parents' marital status on students' scores.
Subject Score Trends
Boxplots highlight that students generally perform worse in Math compared to Reading and Writing.
Ethnic Group Distribution
Visualized with a pie chart and bar chart, showcasing the proportion of students from different ethnic groups.

**Visualizations**
The notebook includes various plots to support the analysis:

Bar charts for gender and ethnic group distributions.
Heatmaps for analyzing relationships between parental background and student performance.
Boxplots to assess the distribution of scores in different subjects.

**How to Use**
Clone the repository:
git clone <repository-url>

Install the required Python libraries:
pip install pandas numpy matplotlib seaborn

Open the Jupyter Notebook to explore the analysis:
jupyter notebook Student_Data_Analysis.ipynb

**Conclusion**
The analysis reveals that:
Gender and parental education significantly influence student performance.
Students struggle the most in Math.
Parental marital status has little to no impact on scores.

**Future Work**
Investigate additional factors that might influence student performance.
Build predictive models using machine learning to forecast student scores.

**Telecom Churn Data Analysis:**
Analysed using numpy, pandas, matplotlib and seaborn
