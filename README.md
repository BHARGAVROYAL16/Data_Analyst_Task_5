# Data_Analyst_Task_5## What I Have Done

In this task, I performed a complete exploratory data analysis (EDA) on the Titanic dataset, following the steps outlined in **Data-Analyst-Task-5.pdf**. Here’s a summary of what I accomplished:

---

### 1. **Data Loading and Setup**
- Imported essential libraries: `numpy`, `pandas`, `matplotlib`, and `seaborn`.
- Loaded the Titanic dataset (`train.csv`) into a pandas DataFrame.
- Set up visualization styles for consistency and clarity.

---

### 2. **Basic Data Exploration**
- Used `.info()` to inspect the structure and data types of the dataset.
- Used `.describe()` to view summary statistics for all numerical columns.
- Checked for missing values and noted that `Age`, `Cabin`, and `Embarked` have missing data.
- Used `.value_counts()` to analyze the distribution of key categorical features:
  - **Survived:** 38.4% survived, 61.6% did not.
  - **Pclass:** Most passengers were in 3rd class (55.1%).
  - **Sex:** 64.8% male, 35.2% female.
  - **Embarked:** 72.4% embarked from Southampton.

---

### 3. **Advanced Visualizations**
- **Pairplot:** Created a pairplot of numerical variables colored by survival status to explore relationships at a glance.
- **Correlation Heatmap:** Generated a heatmap to visualize correlations between key numerical features (e.g., Pclass, Age, Fare, SibSp, Parch, Survived).

---

### 4. **Detailed Plots**
- **Histograms:** Plotted distributions of Age, Fare, SibSp, and Parch, separated by survival status.
- **Boxplots:** 
  - Compared Age and Fare distributions by survival status.
  - Compared Age and Fare distributions by passenger class.
- **Scatterplots:** 
  - Visualized Age vs. Fare colored by survival.
  - Visualized SibSp vs. Parch (family size) colored by survival and sized by fare.

---

### 5. **Analysis and Observations**
- Wrote detailed observations for each step and visualization, including:
  - Survival was higher among first-class passengers and those who paid higher fares.
  - Most passengers were young adults; higher fares and higher class were correlated.
  - Large families tended to have lower survival rates.
  - Noted data quality issues like missing values in Age and Cabin.

---

### 6. **Summary of Insights**
- Summarized the main findings, such as:
  - Socio-economic status (class and fare) had a strong impact on survival.
  - Gender and age also played important roles.
  - Data skewness and missing values should be addressed in further analysis.

---

### 7. **Saved Visualizations**
- Saved all plots (pairplot, heatmap, histograms, boxplots, scatterplots) as image files for documentation and reporting.

---

**In summary:**  
I systematically explored, visualized, and interpreted the Titanic dataset, following best practices in data analysis. My work provides a clear foundation for further statistical modeling or machine learning on this classic dataset.

