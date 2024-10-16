### Key Features of `sns.pairplot`:

1. **Plots All Pairwise Relationships**:
   - For a dataset with `n` numerical columns, `pairplot` creates an $ n \times n $ grid of subplots.
   - Each off-diagonal plot is a scatter plot showing the relationship between two numerical variables.
   - For $ n $ columns, there are $\binom{n}{2}$ scatter plots and $n$ diagonal plots.

2. **Diagonal Plots (Histograms or KDEs)**:
   - By default, `pairplot` plots histograms for the diagonal cells to show the distribution of each numerical variable.
   - You can change this to kernel density estimation (KDE) using the `diag_kind` argument.

3. **Hue (Color Coding by Category)**:
   - Use the `hue` parameter to color-code the scatter plots by a categorical variable (like species, sex or Island).
   - This allows you to see how different categories are distributed across pairs of numerical variables.

4. **Customization**:
   - You can customize marker styles, palettes, plot size, and other visual aspects of the grid.
   
### Example Code:

```python
sns.pairplot(penguins, hue="species", diag_kind="kde")
plt.show()
