# DSA2101 project: Exploring the Relationship Between Fishing Industry and Income Level

## Overview
This repository contains the code and findings of a group project conducted using data from the TidyTuesday repository. The project aimed to explore and visualize real-world data to answer a meaningful question related to the fishing industry and its relationship with income level across different countries.

## Project Details
- **Task**: The task involved selecting one topic, formulating a meaningful question, answering it with three data visualizations using ggplot2, and documenting methods and findings in a write-up.
- **Question**: How does a country’s fishing industry relate to its income level?
- **Hypothesis**: We hypothesized that specific trends exist within the fishing industry that varies according to the income level of the countries. Many interconnected factors pertinent to national income can significantly influence the development and dynamics of specific industries within a nation.
- **Datasets Used**: We used the following datasets:
  - **captured_vs_farmed**: Contains information on trends in fishery production over the years across different income groups.
  - **production**: Provides data on the trends in fish species produced over the years across different income groups.
  - **consumption**: Includes data on the level of fishery consumption across countries categorized by income groups worldwide.
- **Source Data**: Data for this project was sourced from the [TidyTuesday repository](https://github.com/rfordatascience/tidytuesday/blob/master/data/2021/2021-10-12/readme.md).
- **Required Libraries**: The following libraries are required for this project:
  - `tidyverse`: Comprehensive collection of data manipulation tools in R.
  - `maps`: Provides functions to draw geographical maps.
  - `RColorBrewer`: Provides color schemes for maps and other graphics.

## Visualizations
1. **Visualisation 1 (Stacked Area Plot)**: Utilized the *captured_vs_farmed* dataset to create a stacked area plot illustrating trends in fishery production over the years across different income groups.
   
2. **Visualisation 2 (100% Stacked Barplot)**: Employed the *production* dataset to create a 100% stacked barplot illustrating trends in fish species produced over the years across different income groups.
   
3. **Visualisation 3 (Bivariate Choropleth Map)**: Utilized the *consumption* dataset to generate a bivariate choropleth map representing the 2017 level of fishery consumption across countries categorized by income groups worldwide.

## Findings

The project explored the relationship between a country’s fishing industry and its income level using three visualizations. Key findings include:

- **Low-Income Countries**:
  - Exhibit consistently low fishery production due to economic and developmental constraints.
  - Limited access to technology and deep-sea resources constrains fishing activities and consumption.

- **Middle-Income Countries**:
  - Experience shifts in fisheries production, including a surge in aquaculture activities and freshwater fish harvesting.
  - Transitions attributed to technological advancements, efficient resource exploitation, and environmental regulations.

- **High-Income Countries**:
  - Maintain relatively stable fishery industries, with regulatory measures impacting capture fisheries.
  - Higher consumption levels due to advanced resources and infrastructure.

In conclusion, the relationship between income levels and the fishery industry is influenced by economic capacity, infrastructure, and environmental regulations. Understanding these factors is crucial for sustainable development.

