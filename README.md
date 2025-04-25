Title: Exploratory Data Analysis on Titanic Dataset  
Objective: To understand the structure, relationships, and key characteristics of the Titanic dataset using statistics and visualizations.
Dataset Used
Name: Titanic Dataset  
- Source: [Kaggle Titanic Challenge](https://www.kaggle.com/c/titanic)  

Tools & Libraries: 
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Plotly


Steps Performed in the Code:

1. Load Dataset:
   - The Titanic dataset is read using `pandas.read_csv()`.

2. Basic Info:
   - Displays dataset shape, data types, missing values, and statistical summary.

3. Correlation Heatmap:
   - Shows relationships between numerical features using a heatmap.

4. Distribution Plots:
   - Histograms with KDE for numerical columns to understand distributions.

5. Count Plots:
   - Visualizes frequency of categories in categorical columns like `Sex`, `Embarked`, etc.

6. Interactive Scatter Plot:
   - A Plotly-based interactive scatter plot for quick visual inspection of numeric feature relationships, color-coded by a categorical feature.


Usage:
1. Make sure the `titanic.csv` file is in your working directory.
2. Run the Python script using any IDE or Jupyter Notebook.
3. Visual outputs will display one after another with titles indicating what each chart shows.

Note:  
This analysis helps identify trends like survival rate differences by gender, class, age, etc., and serves as a good starting point for feature engineering and predictive modeling.

