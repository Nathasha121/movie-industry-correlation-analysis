# Movie Industry Correlation Analysis

## 📌 Project Overview

A Python-based exploratory data analysis project analyzing approximately **6,820 movies** to investigate relationships between movie characteristics and gross revenue.

The project focuses on data cleaning, exploratory data analysis, correlation analysis, and visualization to identify relationships between factors such as budget, gross revenue, votes, score, year, and runtime.

## 🛠️ Tools & Technologies

- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

## 🔍 Analysis

The project includes:

- Data loading and exploration
- Data cleaning and preprocessing
- Missing-value analysis
- Data type inspection and transformation
- Movie release year analysis
- Sorting and filtering movie data
- Correlation analysis
- Correlation matrix visualization
- Budget vs. gross revenue analysis
- Scatter plot visualization
- Regression analysis using Seaborn

## 📊 Correlation Analysis

Correlation analysis was performed on numerical movie features including:

- Year
- Score
- Votes
- Budget
- Gross Revenue
- Runtime

The analysis identified a strong positive relationship between **movie budget and gross revenue**, with correlation values around **0.72–0.75** in the analysis.

Other notable relationships include:

| Feature Relationship | Approx. Correlation |
|---|---:|
| Budget ↔ Gross Revenue | 0.72–0.75 |
| Votes ↔ Gross Revenue | 0.63 |
| Budget ↔ Votes | 0.49 |
| Score ↔ Votes | 0.39 |

> Correlation indicates a relationship between variables and does not necessarily mean that one variable causes the other.

## 📈 Visualizations

### Correlation Heatmap

The correlation heatmap provides a visual representation of the relationships between the numerical movie features.

![Correlation Heatmap](visualizations/correlation_heatmap.png)

### Budget vs. Gross Revenue

A scatter plot with a regression line was used to examine the relationship between movie budget and gross revenue.

![Budget vs Gross Revenue](visualizations/budget_vs_gross_seaborn.png)

## 💡 Key Insights

- **Budget** showed the strongest positive correlation with **gross revenue** among the analyzed numerical features.
- Movies with higher budgets generally tended to have higher gross revenue in the analyzed dataset.
- **Votes** also showed a positive relationship with gross revenue.
- Budget and votes showed a moderate positive relationship.
- Movie score had a weaker relationship with gross revenue compared with budget and votes.
- The visualizations helped identify patterns and relationships within the movie industry dataset.

## 🚀 Project Workflow

```text
Data Loading
      ↓
Data Exploration
      ↓
Data Cleaning & Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Correlation Analysis
      ↓
Data Visualization
      ↓
Interpretation of Results
      ↓
Key Insights
