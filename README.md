# Video Game Sales Analysis (2024)

## Objective / Problem Statement
The goal of this project is to analyze a dataset containing global video game sales and identify patterns and insights such as:
- Top-selling games and platforms
- Genre popularity across regions
- Regional sales trends and preferences
- Publisher performance

This analysis helps understand the dynamics of the gaming industry and supports data-driven decisions for developers, publishers, and marketers.

---

## Import & Load Data

- Imported essential Python libraries: `pandas`, `matplotlib.pyplot`, `seaborn`, and `kaggle`.
- Downloaded the dataset (`vgchartz-2024.csv`) from Kaggle using the Kaggle API.
- Loaded the dataset into a Pandas DataFrame.
- Displayed the first few rows and dataset info to understand its structure.

---

## Data Cleaning

Data cleaning process:

1. Checked dataset shape and column names.
2. Displayed data types using `.info()`.
3. Used `.describe()` for statistical overview.
4. Checked and handled missing/null values.
5. Dropped irrelevant or unnecessary columns.
6. Checked and removed duplicate entries.
7. Standardized column names for readability.
8. Converted data types where needed.
9. Handled inconsistent entries (e.g., zero or invalid sales).
10. Verified the final cleaned DataFrame.

---

## Data Visualization & Analysis

1. **Top 10 globally best-selling games**  
   → Bar chart sorted by `Global_Sales`.

2. **Most successful platforms globally**  
   → Platform-wise total sales comparison.

3. **Most popular game genres globally**  
   → Pie chart showing genre distribution by `Global_Sales`.

4. **Top 10 publishers by total sales**  
   → Bar chart grouped by `Publisher`.

5. **Regional sales comparison**  
   → Sales breakdown across NA, EU, JP, and Other regions.

6. **Top-selling genres in Japan**  
   → Genre-wise chart filtered using `JP_Sales`.

7. **Correlation between regional sales**  
   → Heatmap showing relationships between regional sales metrics.

8. **Platform popularity by region**  
   → Grouped bar chart showing platform sales across different regions.

All visualizations were created using `matplotlib` and `seaborn`, followed by insights and interpretation.

---

## Conclusion

- **North America** consistently records the highest sales across most platforms and genres.
- **Action** and **Sports** genres dominate global sales charts.
- Certain publishers (e.g., Nintendo) perform exceptionally well in Japan.
- Some platforms (e.g., PS2, DS) lead in global game distribution and success.
- There is a moderate to strong correlation between North American and European sales, while Japanese sales trends differ significantly.

The analysis demonstrates how data visualization can reveal meaningful patterns in the video game industry and support strategic decisions in development, marketing, and publishing.

---

## Files

- `project.ipynb`: Jupyter notebook with full code and analysis.
- `README.md`: Project documentation and summary.

