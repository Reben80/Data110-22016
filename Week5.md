# Week 5: Visualizing Distributions: Histograms and Density Plots

This week, we’ll focus on visualizing distributions using two powerful tools: **histograms** and **density plots**. To dive deeper into these topics, you can explore [Chapter 7: Visualizing Distributions](https://clauswilke.com/dataviz/histograms-density-plots.html) by Claus Wilke.

Histograms and density plots help us understand the distribution of data points, whether we're looking for outliers, clusters, or general trends. Both of these plots have unique strengths, and learning when and how to use them is essential for effective data visualization.

## Types of Plots We’ll Cover:

### 1. Histograms
We’ll start with histograms, which provide a visual representation of the frequency of data points within specified ranges (bins). You’ll learn how to choose the right number of bins and how different bin widths can alter the interpretation of the data.

### 2. Kernel Density Estimation (KDE)
Kernel Density Estimation (KDE) smooths out the data, giving you a continuous estimate of the probability distribution. We’ll explore how KDE can complement histograms by providing a clearer view of the underlying distribution, and how to choose an appropriate bandwidth for your data.

### 3. Comparing Distributions
We’ll discuss how to overlay histograms or density plots to compare distributions between different categories, such as survival rates based on age or passenger class in the Titanic dataset. We’ll also explore the role of color and transparency when visualizing overlapping data.

## Key Concepts to Focus On:
- The importance of choosing the right bin width for histograms.
- How Kernel Density Estimation works and when to use it.
- When to use histograms vs. KDE plots, or when to combine both for a more complete analysis.
- Best practices for color, transparency, and overlays when comparing multiple distributions.

By the end of the week, you’ll have a deeper understanding of how to use histograms and density plots to effectively visualize and interpret distributions.

---

## Practical Examples of Histograms and Density Plots in Action

Histograms and density plots are commonly used in fields such as **statistics**, **machine learning**, and **finance**, where understanding the distribution of data points is critical. Below are some real-world examples:

| **Scenario**                        | **Example**                                                                                         | **Usefulness**                                                                                              | **Plot Type**                  |
|-------------------------------------|-----------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|---------------------------------|
| **Income Distribution**             | Visualizing the distribution of incomes across a population.                                          | Shows how wealth is distributed and highlights income inequality.                                           | Histogram, KDE                 |
| **Test Scores Distribution**        | Analyzing student performance on a standardized test.                                                | Reveals how well the class performed overall and identifies high and low scorers.                            | Histogram                      |
| **Age Distribution by Gender**      | Comparing the distribution of ages for males and females.                                            | Highlights any differences in age distribution between genders, useful for demographic analysis.             | KDE                            |
| **Stock Price Volatility**          | Visualizing the distribution of daily stock price changes.                                           | Shows how often large price changes occur, providing insight into market volatility.                         | Histogram                      |
| **Website Traffic Analysis**        | Analyzing the distribution of website visits over time.                                              | Identifies peak and off-peak hours for website traffic, useful for optimizing server capacity.               | Histogram                      |
| **Survival Rates by Age**           | Comparing the distribution of ages for survivors and non-survivors in the Titanic dataset.            | Reveals age-related trends in survival rates, useful for demographic analysis.                               | KDE, Histogram                 |
| **Medical Data**                    | Analyzing the distribution of cholesterol levels in a patient population.                            | Helps identify normal ranges and outliers in medical diagnostics.                                           | KDE, Histogram                 |

---

## When Histograms and KDE Fall Short

While histograms and density plots are great for visualizing distributions, they have limitations:

### 1. Too Few or Too Many Bins
   - **Problem**: Too few bins obscure detail, while too many bins make the plot noisy.
   - **Solution**: Experiment with bin widths to find the best balance.

### 2. Small Sample Sizes
   - **Problem**: With small datasets, histograms can become sparse, and KDE may over-smooth the data.
   - **Solution**: Consider using box plots or other summary statistics when the sample size is small.

### 3. Discrete Data
   - **Problem**: KDE works best for continuous data and may not be ideal for discrete data, such as counts.
   - **Solution**: Use histograms for discrete data or consider bar plots as an alternative.

### 4. Complex Multimodal Distributions
   - **Problem**: KDE may not always capture the complexity of multimodal distributions well.
   - **Solution**: Combine histograms with KDE or use more advanced tools like violin plots to better represent the data.

### 5. Overplotting
   - **Problem**: Overlaying multiple histograms or KDE plots can become cluttered and hard to interpret.
   - **Solution**: Use transparency (alpha) to differentiate overlapping distributions or consider facet plots.

---

## Understanding Bandwidth in KDE

One of the key decisions when creating a KDE plot is selecting the appropriate bandwidth. Bandwidth controls how smooth or detailed the density estimate is, with smaller bandwidths capturing more detail but potentially adding noise, and larger bandwidths providing a smoother, less detailed curve.


---

### Week 5 Supplement
1. [Python Lab](Week5_Code_Titanic.ipynb)
2. [Week 5 Python Assignment](Week_5_Python_Assignment.md)


