# Week [10 and 11]: Maps and Data Visualization

## Overview
This week, we delved deeper into the use of maps for data visualization, focusing on geographic data representation through heatmaps and interactive layering. We used the **Folium** package to explore real-world datasets and create impactful visualizations.

## Key Topics
- **Introduction to Data Visualization with Maps**
  - How maps help in identifying spatial patterns
  - The importance of visual storytelling in geographic data
- **Historical and Contemporary Use Cases**
  - Maps in public health, urban planning, and crime analysis

## Example 1: John Snow's Map
- **Historical Context**: John Snow's 1854 cholera outbreak map is a classic example of how mapping data can uncover hidden patterns.
- **Key Insights**:
  - By mapping cholera cases, Snow demonstrated the link between outbreaks and contaminated water sources.
  - His map became a pioneering example of spatial analysis in epidemiology.
- **Discussion Points**:
  - How spatial data can challenge existing assumptions (e.g., miasma theory in Snow's time).
  - The role of visualization in driving actionable insights and decision-making.

## Example 2: Heatmaps with Modern Datasets
### Part 1: Baltimore Arrests Heatmap
Using the **BPD Arrests Dataset**, we visualized arrest hotspots in Baltimore:
- **Objective**: Highlight areas with high arrest activity.
- **Visualization**:
  - A heatmap revealed concentrated hotspots, emphasizing areas requiring further investigation or policy interventions.

### Part 2: DC Crime and Liquor Licenses
#### Crime Heatmap
Using the **Crime_Incidents_DC_2024.csv** dataset:
- **Objective**: Visualize the geographic distribution of crime incidents across Washington, DC.
- **Visualization**:
  - A heatmap displayed crime hotspots.

#### Liquor Licenses Heatmap
Using the **Liquor_Licenses_DC.csv** dataset:
- **Objective**: Explore the relationship between liquor license locations and crime hotspots.
- **Visualization**:
  - A heatmap of liquor license locations enabled visual correlation with crime density.

### Part 3: Combined Map with Layer Control
- **Objective**: Provide an interactive map where users can toggle between layers for better insight.
- **Layers**:
  1. Crime Incidents
  2. Liquor Licenses
- **Visualization**:
  - An interactive map was created with both heatmaps as separate layers.
  - Users could choose which layer(s) to view using a layer control feature.

## Activities
1. **Baltimore Arrests Heatmap**:
   - Students visualized arrest hotspots and discussed potential contributing factors.
2. **DC Crime and Liquor Heatmaps**:
   - Students created individual heatmaps and reflected on spatial correlations.
3. **Combined Map Exercise**:
   - Students built an interactive map with selectable layers for crime and liquor license data.

## Tools and Skills
- **Tools**: Folium, Pandas, and Python for map creation and data visualization.
- **Skills**:
  - Cleaning and analyzing geographic datasets
  - Designing effective heatmaps
  - Implementing layer controls for interactive maps

## Takeaways
- Heatmaps are effective for visualizing density and identifying spatial relationships.
- Interactive maps with layer controls enhance user experience and analytical depth.
- Geographic data provides valuable insights into urban planning, public safety, and resource distribution.

## Assignments
- Create a combined heatmap visualization for the **BPD_Arrests.csv** dataset, with  two interactive layers based on **Gender** (e.g., one layer for arrests involving males and another for arrests involving females). 
- Reflect on the patterns revealed in each gender-based layer and discuss any potential insights or societal implications.
- Present your findings by explaining how the spatial distribution differs or overlaps between the two layers.
- Try to work on The other Crime Incidents and create two different data visualizaions. 
---

## Assignments
- Create a combined heatmap visualization for the **BPD_Arrests.csv** dataset, with at least two interactive layers based on **Gender** (e.g., one layer for arrests involving males and another for arrests involving females). 
- Reflect on the patterns revealed in each gender-based layer and discuss any potential insights or societal implications.
- Present your findings by explaining how the spatial distribution differs or overlaps between the two layers.

**Notes**:
1. The **BPD_Arrests.csv** dataset is large and can be found in the MS Teams Challenge folder named **Dataset**. Ensure you handle the dataset efficiently when processing the data for visualization.
2. Class components for this week include:
   - **Google Colab Notebooks**: 
   - [Google Colab:John Snow's Map ](Week11_part1.ipynb)
   - [Google Colab: Crime and Liquor Licences](Week11_part2.ipynb)
   - **Datasets**:
     - `BPD_Arrests.csv`
     - `Crime_Incidents_DC_2024.csv`
     - `Liquor_Licenses_BC.csv`
     - `Liquor_Licenses_DC.csv`
  
