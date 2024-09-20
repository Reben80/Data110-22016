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


[📝 Week 3 Assignment: Line and Scatter Plots](Week3_Assignment.md)

This assignment will challenge you to create various line and scatter plots, customize their appearance, and visualize mathematical functions using Matplotlib. Good luck!



### Remark 


1. 📈 [Line Plots Tutorial](Week3_line_plots.ipynb)
   - Learn to visualize and creating and customizing line plots
   - Explore various line styles, colors, and markers

2. 🔵 [Scatter Plot Tutorial](Week3_Scatter_Plot.ipynb)
   - Learn to visualize data points with scatter plots

These notebooks contain hands-on examples and code snippets that complement our lecture material. They're designed to help you practice and reinforce your understanding of Matplotlib's capabilities.

Happy coding! 💻✨





_______

You can find all course materials in our Data110-22016 GitHub Repository.


