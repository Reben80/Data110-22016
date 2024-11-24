# Week 12 Summary

This week's focus was on exploring and visualizing data using Python, with an emphasis on geographic and demographic data. For the second week in a row, following Week 11's focus on data, we continued to dive deeper into creating impactful visualizations. Below is a summary of the key activities and techniques covered, including the introduction of new packages.

## 1. Geographic Visualizations
- Created **choropleth maps** using Plotly to display demographic and economic data:
  - Global GDP and population maps.
  - U.S. unemployment rates by county.
  - Focused choropleth maps for Maryland counties.
- Discussed the practicality of using Python versus simpler tools like SankeyMATIC for specific visualizations.

## 2. Hierarchical and Comparative Visualizations
- Generated **treemaps** with squarify:
  - Highlighted the top countries by population.
  - Displayed population distribution by region.
- Developed a **Sankey diagram** to depict world population flows from global to regional and country levels.

## 3. Interactive State-Level Data
- Visualized population and GDP of top U.S. states using:
  - **Bar charts** for population.
  - **Bubble charts** for GDP.

## 4. New Tools and Packages
- Continued use of familiar packages like `pandas` and `numpy` for data manipulation.
- Introduced:
  - **`plotly`**: For creating interactive visualizations such as choropleth maps and bubble charts.
  - **`squarify`**: For generating treemaps, a new visualization technique to represent hierarchical data.
  - **GeoJSON integration**: To create custom geographic visualizations, such as U.S. county-level maps.


## Datasets Used

This week involved working with a variety of datasets to create meaningful visualizations:

1. **World Countries Data**:
   - URL: `https://raw.githubusercontent.com/Reben80/Data110-22016/refs/heads/main/dataset/world_countries.csv`
   - Key Features: Population, GDP, and regional data for countries worldwide.

2. **U.S. States Population Data**:
   - URL: `https://raw.githubusercontent.com/Reben80/Data110-22016/refs/heads/main/dataset/US_State_abbrev.csv`
   - Key Features: State abbreviations and 2024 population estimates for all U.S. states.

3. **U.S. County Unemployment Data**:
   - URL: `https://raw.githubusercontent.com/plotly/datasets/master/fips-unemp-16.csv`
   - Key Features: FIPS codes and unemployment rates for U.S. counties.

4. **GeoJSON for U.S. Counties**:
   - URL: `https://raw.githubusercontent.com/plotly/datasets/master/geojson-counties-fips.json`
   - Key Features: GeoJSON file defining boundaries for U.S. counties, used for choropleth maps.

These datasets provided a foundation for exploring geographic and demographic data across different scales, from global to local levels.

5. [Week 12 Google Colab](Week12.ipynb)

## 5. Summary
- Practical application of libraries such as  `plotly` and `squarify`.
- Emphasis on creating interactive and engaging visualizations for better understanding of geographic and demographic trends.
- Consideration of the complexity of using Python for specific tasks, suggesting alternative tools where appropriate.

