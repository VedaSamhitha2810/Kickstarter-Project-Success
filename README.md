### Kickstarter Projects Analysis 📊

This repository contains an analysis of Kickstarter projects using Python and various data analysis libraries.

#### Dataset 📄
The dataset (`kickstarter_projects.csv`) includes information about Kickstarter projects such as ID, name, category, subcategory, country, launch date, deadline, funding goal, pledged amount, number of backers, project state, and duration in days.

#### Analysis Highlights 🔍
- **Data Cleaning and Preparation**: 
  - Converted `Launched` and `Deadline` columns to datetime format.
  - Calculated `Duration_in_Days` as the difference between `Deadline` and `Launched`.

- **Descriptive Statistics**: 
  - Analyzed basic statistics like mean, median, and quartiles for numeric columns (`Goal`, `Pledged`, `Backers`, `Duration_in_Days`).

- **Visualization**: 
  - Utilized matplotlib and seaborn for visualizing:
    - Correlation heatmap of `Goal`, `Pledged`, and `Backers`.
    - Pie chart and bar chart for project success rates.
    - Word cloud for project categories.
    - Box plots for outliers in `Goal`, `Pledged`, and `Backers`.
    - Bar chart for the number of projects launched per category.
    - Line chart showing the trend of Kickstarter projects over the years.
    - Stacked bar chart depicting project outcomes by duration range.

#### Conclusion 📝
This analysis provides insights into Kickstarter project trends, success rates, category-wise distributions, and factors influencing project outcomes.

#### Repository Structure 📂
- `kickstarter_projects.csv`: Raw dataset.
- `kickstarter_analysis.ipynb`: Jupyter notebook containing Python code for analysis.
- `README.md`: Markdown file summarizing the analysis (you're currently reading this).

#### Requirements 🛠️
Ensure you have the following Python libraries installed:
- pandas
- matplotlib
- seaborn
- wordcloud

#### How to Run ▶️
1. Clone this repository.
2. Install the required Python libraries (`pip install -r requirements.txt`).
3. Run the Jupyter notebook (`kickstarter_analysis.ipynb`) to reproduce the analysis.
