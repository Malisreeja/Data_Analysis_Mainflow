# Data_Analysis_Mainflow
Objective
This project analyzes a dataset of student exam scores to explore relationships between study habits, gender, and academic performance. Using Python and fundamental data analysis techniques, the project answers specific analytical questions and visualizes findings.

📂 Dataset
File: student-mat.csv

Source: UCI Machine Learning Repository – Student Performance Dataset

Key Columns:

G1, G2, G3 → Grades for three terms

studytime → Weekly study time (in hours)

sex → Gender (Male/Female)

🛠 Technologies Used
Python

Libraries:

pandas → Data loading, cleaning, and analysis

numpy → Mathematical calculations

matplotlib & seaborn → Data visualization

📜 Project Steps
1️⃣ Data Loading
Loaded dataset with pandas.read_csv()

Previewed data using .head()

2️⃣ Data Exploration
Checked missing values with .isnull().sum()

Viewed column data types using .dtypes

Found dataset size with .shape

3️⃣ Data Cleaning
Handled missing values (replaced with median or removed rows)

Removed duplicates with .drop_duplicates()

4️⃣ Data Analysis Questions Answered
Average score in math (G3)

Count of students scoring above 15 in G3

Correlation between study time and final grade (G3)

Gender-wise average final grades comparison

5️⃣ Data Visualization
Histogram of final grades (G3)

Scatter plot: Study time vs. Final grade

Bar chart: Average G3 scores for Male vs. Female

📈 Key Insights
Average final grade (G3) was calculated directly from the dataset.

Found positive/negative correlation (depending on dataset) between study time and performance.

Compared performance trends by gender.
Author 
MALI SREEJA REDDY
Edit
jupyter notebook
Run each cell in sequence to reproduce results.
