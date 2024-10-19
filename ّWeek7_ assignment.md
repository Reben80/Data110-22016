# Focused Iris Data Analysis Assignment

## Objective
In this assignment, you will perform specific data visualization and analysis tasks on the Iris dataset using Python, pandas, matplotlib, and seaborn.

## Dataset
You will be working with the 'Iris' dataset, which is available in the seaborn library. This dataset contains measurements of iris flowers, including sepal length, sepal width, petal length, petal width, and species.

## Tasks

### 1. Data Visualization (60 points)

#### 1.1 Pair Plot (15 points)
Create a pair plot of all features in the Iris dataset, color-coding by species. Include an overall title for the plot.

#### 1.2 Bar Plot (10 points)
Create a bar plot showing the average sepal length for each iris species.

#### 1.3 Box Plot (10 points)
Create a box plot showing the distribution of petal widths for each species.

#### 1.4 Grouped Bar Plot (15 points)
Create a grouped bar plot showing the average sepal and petal lengths by species.

#### 1.5 Violin Plot (10 points)
Create a violin plot showing the distribution of sepal length for each species.

### 2. Data Analysis (40 points)

#### 2.1 Aggregation (25 points)
a) Calculate and display the mean, minimum, and maximum values of all numerical features (sepal length, sepal width, petal length, petal width) for each species.
b) Count and display the number of samples in each species.

#### 2.2 Interpretation (15 points)
Provide a brief interpretation (2-3 sentences) for each of the visualizations and the aggregated data. What insights can you draw about the different iris species based on these results?

## Submission Guidelines
- Submit your work as a Jupyter Notebook (.ipynb file).
- Include comments explaining your code.
- Ensure all visualizations are properly labeled with titles, axis labels, and legends where appropriate.
- Include your interpretations in markdown cells following each visualization and analysis.

## Grading Criteria
- Correct implementation of required visualizations and analyses (70%)
- Code quality and comments (15%)
- Interpretation of results (15%)

Total possible points: 100

## Hints
- Use `sns.pairplot()` for the pair plot.
- For the grouped bar plot, you'll need to reshape your data using `pd.melt()`.
- Use `groupby()` and `agg()` functions for the aggregation task.
- Pay attention to figure sizes and plot aesthetics for clarity.

Good luck!
