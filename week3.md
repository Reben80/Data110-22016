### Week 3: Line and Scatter Plots with Matplotlib in Python

This week, we talked about creating and customizing line and scatter plots using Matplotlib, a powerful plotting library in Python. Here's what we coverd:

1. **Matplotlib Basics**: 
   - Learn to import Matplotlib and create basic plots:
     ```python
     import matplotlib.pyplot as plt
     import numpy as np

     x = np.linspace(0, 10, 100)
     plt.plot(x, np.sin(x))
     plt.show()
     ```
   - Understand how to use `plt.plot()` for both line plots and scatter plots

2. **Line Plots**: 
   - Create simple line plots using `plt.plot()`:
     ```python
     x = np.linspace(-2, 4, 100)
     y = x**2 - 2*x + 1
     plt.plot(x, y)
     plt.title("Quadratic Function")
     plt.xlabel("X-axis")
     plt.ylabel("Y-axis")
     ```
   - Plot multiple lines on the same graph and add a legend

3. **Scatter Plots**:
   - Create scatter plots using both `plt.plot()` with markers and `plt.scatter()`:
     ```python
     x = np.random.rand(50)
     y = np.random.rand(50)
     plt.scatter(x, y)
     plt.title("Random Scatter Plot")
     ```
   - Customize scatter plots by changing marker size, color, and style

4. **Plot Customization**: 
   - Explore various customization options:
     ```python
     plt.plot(x, y, color='red', linestyle='--', linewidth=2, marker='o')
     ```
   - Learn to add and customize titles, labels, and legends

5. **Multiple Functions**: 
   - Plot multiple functions on the same graph:
     ```python
     x = np.linspace(-10, 10, 100)
     plt.plot(x, x**2, x, x**3, x, np.sin(x))
     plt.legend(['x^2', 'x^3', 'sin(x)'])
     ```

6. **Styling and Comparison**: 
   - Explore and apply different styles:
     ```python
     plt.style.use('seaborn-whitegrid')
     print(plt.style.available)  # List all available styles
     ```
   - Compare the same plot with different styles

7. **Plotting Mathematical Functions**: 
   - Visualize various mathematical functions using line plots:
     ```python
     x = np.linspace(-10, 10, 100)
     plt.plot(x, np.tan(x))
     plt.title("Tangent Function")
     plt.xlim(-2, 2)
     plt.ylim(-10, 10)
     ```
   - Use `plt.xlim()` and `plt.ylim()` to set appropriate axis limits

Throughout the week, you'll also learn about:
- Customizing line properties (color, style, width)
- Adjusting marker properties in scatter plots
- Setting axis properties and limits
- Combining line and scatter elements in a single plot

### Week 3 Assingment 
![Week3_Assignment.md](Week3_Assignment.md)

Note: For practical examples and the Python code covered in this week's topics, please refer to the following Jupyter notebooks in our course GitHub repository:

- ![Week3_line_plots.ipynb](Week3_line_plots.ipynb)
- ![Week3_Scatter_Plot.ipynb](Week3_Scatter_Plot.ipynb)

These notebooks, located in the main folder of our GitHub repository, contain the actual Python code demonstrating the concepts we've covered regarding line plots and scatter plots. They serve as valuable resources for your hands-on practice and reference.
You can find all course materials in our Data110-22016 GitHub Repository.


