# Harshada-Elevate_-labs_-task-2
📁 Dataset Used

Titanic Dataset from Kaggle

File Name: Titanic-Dataset.csv

🔍 Summary of Tasks Performed

✅ 1. Generate Summary Statistics

We used df.describe() to view:

Mean, Median, Min, Max

Standard Deviation

Quartiles for numeric features

This helped us understand the range and distribution of variables like Age, Fare, SibSp, and Parch.

✅ 2. Create Histograms and Boxplots for Numeric Features

Created Histograms to visualize frequency distribution for:

Survived, Pclass, Age, SibSp, Parch, Fare

Adjusted bins and axis limits for clarity.

Created Boxplots to identify:

Median values

Interquartile ranges (IQR)

Outliers visually for each numeric column.

✅ 3. Use Pairplot/Correlation Matrix for Feature Relationships

Used Correlation Matrix with heatmap to analyze pairwise correlations between numeric features.

Created a Pairplot (with hue='Survived') to:

Visualize relationships between key variables

Observe how features group across survival outcome

✅ 4. Identify Patterns, Trends, or Anomalies

Observed:

High Fares and 1st class passengers had higher survival rates

Many outliers in Fare

Younger passengers had better survival chances

Large families (high SibSp, Parch) correlated with lower survival

✅ 5. Make Basic Feature-Level Inferences from Visuals

Fare: Strong positive correlation with survival

Pclass: 3rd class had noticeably lower survival rates

SibSp/Parch: Lower values (smaller families) showed better outcomes

Age: Very young passengers had higher survival in general

These insights help determine which features to prioritize for modeling.

📊 Tools & Libraries Used

Google Colab (Python 3)

pandas, numpy

matplotlib, seaborn

sklearn.preprocessing for scaling (in prior steps)

📂 Project Files

Titanic-Dataset.csv - Raw data file

titanic_eda.ipynb - Colab notebook with all analysis

