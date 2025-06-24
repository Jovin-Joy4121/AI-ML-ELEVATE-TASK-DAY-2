🧪 Task 2: Exploratory Data Analysis (EDA) – Titanic Dataset
📌 Objective
To explore and understand the Titanic dataset using descriptive statistics and visualizations, uncovering relationships, patterns, and potential feature-level insights useful for building predictive models.

🛠️ Tools & Libraries Used
Python
Pandas – Data handling & summary stats
Seaborn – Statistical visualizations
Matplotlib – Basic plotting
Plotly Express – Interactive plots
📂 Dataset Description
The dataset (titanic_cleaned.csv) includes passenger data from the Titanic, such as:

Survived (target): 0 = No, 1 = Yes
Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
Sex, Age, Fare, SibSp, Parch
Embarked (C, Q, S) – encoded
All categorical columns are encoded and missing values handled
🔍 Key Steps in EDA
1️⃣ Summary Statistics
Used .describe() and .value_counts() to analyze distributions of numeric and categorical features
Identified imbalances in gender, class, and survival rates
2️⃣ Visual Exploration
Histograms for Age and Fare to understand distribution shape
Boxplots to detect outliers in numeric columns
Correlation Heatmap to study linear relationships between numeric features
Pairplot to observe survival clusters across features
Bar Plots for survival comparison by Sex and Pclass
Scatter Plot (Fare vs Age) using Plotly for interactive analysis
📈 Feature-Level Inferences
Feature	Insight
Sex	Females had significantly higher survival rates
Pclass	1st class passengers had highest survival
Age	Young children had better survival chances
Fare	Higher fare → higher probability of survival
Correlation	Fare and Survived had positive correlation; Sex (encoded) negatively correlated with Survived
🧠 Insights & Observations
Gender and class are strong indicators of survival.
Visuals revealed clear separation between survivors and non-survivors across some features.
Outliers exist in Fare and Age, which may affect model training if not handled.
📁 Files Included
titanic_cleaned.csv – Preprocessed dataset
titanic_eda.ipynb – Jupyter/Colab notebook for EDA
README.md – This documentation file
🚀 Next Steps
Proceed to Feature Engineering or Modeling (e.g., logistic regression, decision trees)
Use insights gained here to select and prioritize features
