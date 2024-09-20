# Week 3: Matplotlib Line and Scatter Plots Assignment

## Overview

In this assignment, you'll practice creating various line and scatter plots using Matplotlib in Python. You'll work with different mathematical functions to create diverse and interesting plots, and explore different plotting styles.

## Tasks

### 1. Setup and Styles
- Import the necessary libraries (Matplotlib and NumPy)
- Use the following code to print out all available styles:
  ```python
  import matplotlib.pyplot as plt
  print(plt.style.available)
  ```
- Set the default style to 'seaborn-whitegrid'
- Choose one additional style from the available list to use later in the assignment

### 2. Basic Line Plot
- Create a plot of the quadratic function $f(x) = x^2 - 2x + 1$ over the range $[-2, 4]$
- Use `plt.plot()` to create the plot

### 3. Multiple Lines
- Create a plot with the following three functions on the same graph:
  - $f(x) = x^3$
  - $g(x) = e^x$
  - $h(x) = \log(x)$ (for $x > 0$)
- Use different colors for each line
- Add a legend to distinguish between the functions

### 4. Styling Lines
- Create a plot with the following functions, each with a different color and line style:
  - $f(x) = x^2$
  - $g(x) = x^3$
  - $h(x) = x^4$
  - $i(x) = x^5$
- Demonstrate at least 4 different color specification methods

### 5. Axes Limits and Scaling
- Plot the function $f(x) = \frac{1}{x^2 + 1}$ over the range $[-10, 10]$
- Set appropriate custom x and y limits to showcase the function's behavior
- Create another plot of the same function with reversed x and y axes
- Demonstrate the use of `plt.axis('tight')` and `plt.axis('equal')`

### 6. Labels and Legends
- Create a plot of $f(x) = \sqrt{x}$ and $g(x) = x^{\frac{1}{3}}$ for $x \geq 0$
- Add a proper title, x-label, y-label, and legend

### 7. Basic Scatter Plot
- Generate 50 random points using `np.random.rand()` for both x and y
- Create a scatter plot of these points using `plt.plot()` with the 'o' marker
- Create the same scatter plot using `plt.scatter()`

### 8. Customizing Scatter Plots
- Generate data for the function $f(x) = x \sin(x)$ over the range $[0, 4\pi]$
- Create a scatter plot of this data with a line connecting the points
- Customize the plot by changing the marker size, line width, marker face color, marker edge color, and marker edge width

### 9. Combined Plot
- Plot the function $f(x) = x \cos(x)$ over the range $[-2\pi, 2\pi]$
- Add scatter points for x values at every $\frac{\pi}{4}$ interval
- Use different colors and styles for the line and scatter components

### 10. Custom Plot with Alternative Style
- Choose two or more functions from the following list:
  - $f(x) = \tan(x)$
  - $g(x) = x e^{-x^2}$
  - $h(x) = \frac{\sin(x)}{x}$  (with appropriate handling for $x=0$)
  - $i(x) = \arctan(x)$
  - $j(x) = \frac{1}{1 + e^{-x}}$  (logistic function)
- Create a custom plot that combines at least 4 concepts learned (e.g., multiple functions, scatter points, custom colors, line styles, limits, labels, and legend)
- Use the alternative style you chose in Task 1 for this plot
- Add comments explaining your choices, the significance of the functions you chose, and how the alternative style affects the plot's appearance

### 11. Style Comparison
- Choose one of your previous plots (Tasks 2-9)
- Recreate it using three different styles: the default style, 'seaborn-whitegrid', and your chosen alternative style
- Compare and contrast the appearances, discussing which style might be most appropriate for the specific data being plotted

## Submission Guidelines

1. Complete the assignment in Google Colab.
2. Name your notebook `matplotlib_assignment.ipynb`.
3. Ensure all code cells are executed and outputs are visible.
4. Include comments explaining your code where necessary.
5. Save a copy of your completed notebook to your GitHub repository:
   - In Google Colab, go to File > Save a copy in GitHub.
   - Select your repository and choose a path for the file.
   - Commit the file directly to the main branch of your repository.
6. Submit the following to your instructor:
   - The direct link to your `matplotlib_assignment.ipynb` file on GitHub.
   - The link to your GitHub repository.

## Grading Criteria

Your assignment will be evaluated based on:
- Correct implementation of each task
- Code clarity and efficiency
- Proper use of Matplotlib features, including styles
- Creativity in the custom plot
- Proper commenting and explanation of your code
- Thoughtful comparison of different styles
- Successful submission to GitHub

Good luck and happy Python coding!
