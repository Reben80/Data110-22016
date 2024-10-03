# Assignment: Uncovering Insights from the Titanic Dataset

## Objective:
This assignment focuses on using the Titanic dataset (available in the Seaborn library) to extract meaningful insights, emphasizing histograms and KDE plots. Instead of just plotting graphs, the focus is on interpreting the results, asking thoughtful questions, and connecting findings to real-world scenarios.

## Instructions:
You are required to perform a detailed analysis of the Titanic dataset using histograms and KDE plots to uncover insights. Use visualizations to support your claims, but primarily focus on interpreting the data.

### Loading the Dataset:
The Titanic dataset can be accessed from the Seaborn library. Use the following code to load the dataset:

```python
import seaborn as sns
import pandas as pd

# Load Titanic dataset
titanic = sns.load_dataset('titanic')

# View the first few rows of the dataset
titanic.head()
```


## Assignment Outline

### Part 1: Understanding the Dataset
1. **Task 1: Dataset Overview**  
   - Briefly describe the Titanic dataset. What kind of information is contained in each column?  
   *Deliverable*: Write a paragraph summarizing the dataset based on your exploration.

### Part 2: Fare and Survival Analysis
2. **Task 2: Fare Distribution**  
   - Plot a histogram and KDE for the distribution of fares paid by passengers.  
   *Question*: What trends or outliers do you observe in the fare distribution? How might fare impact survival rates?

3. **Task 3: Fare and Survival Rates**  
   - Create a KDE plot to compare the fare distributions for survivors and non-survivors.  
   *Question*: Does fare seem to have influenced survival? What do the distributions suggest about socioeconomic status and survival?

### Part 3: Class, Fare, and Survival Insights
4. **Task 4: Passenger Class, Fare, and Survival**  
   - Create histograms and KDE plots to compare fare distributions across different passenger classes (`Pclass`) and analyze survival rates for each class.  
   *Question*: What patterns do you observe in fare distribution and survival rates across different classes? How does this reflect the socioeconomic divisions on the Titanic?

### Part 4: Age and Survival
5. **Task 5: Age of Survivors and Non-Survivors**  
   - Create KDE plots to compare the age distributions of survivors and non-survivors.  
   *Question*: What trends do you notice in the age distribution of survivors compared to those who did not survive? How might age have impacted survival rates?

6. **Task 6: Pyramid Histogram for Age Survival by Sex**  
   - Create a **pyramid-style histogram** (also known as a population pyramid) for age, showing survival data split by sex. If possible, attempt to find or create one.  
   *Question*: What can you infer from the age and sex distribution in relation to survival rates?

### Optional Task: Exploring Additional Visualizations
7.  **Task 7 (Optional): Bar Graph, Line Plot, and Scatter Plot**  
   - Create a bar graph, line plot, and scatter plot using the Titanic dataset.  
   *Suggestions*: You can explore variables like survival rates, passenger class, age, or fare in these plots.
   *Question*: What additional insights do these visualizations provide that weren't evident from the histograms and KDE plots?



## Key Focus:

- **Emphasis on histograms and KDE**: Ensure all analyses use histograms and KDE where appropriate.
- **Critical thinking**: Think critically about the dataset’s limitations, potential biases, and how these factors might influence conclusions.
- **Historical context**: Tie findings to the historical context of the Titanic, particularly socioeconomic factors and family structures.

## Submission Requirements:

- Work in **Google Colab** for this assignment.
- After completing your work, save your file and link it to **GitHub**.
- Post the **GitHub link** of your work into **MS Teams** as your final submission.
- Ensure visualizations include brief descriptions and answers to each question.
- Your code must be well-commented and clean.
