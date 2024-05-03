# Diet-and-the-Environment-Unveiling-the-Impact-Through-Data-Visualization


## Project Overview
This repository contains the visualization code developed for a coursework assignment as part of the COMP4037 Research Methods module. The assignment tasked students with creating advanced data visualizations to interpret and present a massive dataset detailing the environmental impacts of various diets. The data was collected from over 55,000 consumers and 38,000 farms across 119 countries, focusing on the relationship between diet, food consumption, and environmental sustainability.

## Coursework Description
The primary goal of this coursework was to explore the environmental impacts associated with different diets including meat, fish, vegetarian, and vegan options. Utilizing data visualization tools, we sought to address several research questions:

Which diet is most beneficial for the environment?
What disparities exist between the environmental impacts of different diets?
How do age and gender influence dietary impacts on the environment?
The project aimed to improve understanding of the extensive dataset provided by researchers from the University of Oxford, who noted the absence of visual representations in their initial study. Our task was to create meaningful visualizations that not only present the data but also enable discovery of patterns, deviations, and hierarchical relationships.

## Visualizations

Treemap: This visualization categorizes environmental impacts by diet group, age, and gender, showcasing the hierarchical distribution of impact through varying sizes and colors.

Waterfall Charts: 
By Age Group: Illustrates the cumulative environmental impact across different age groups, highlighting how impacts increase with age.
By Diet Group: Breaks down the environmental impacts by diet type, from high meat consumption to vegan diets, emphasizing the significant differences in environmental footprints.

Each visualization was crafted using Plotly, a powerful graphing library that supports complex, interactive visuals in Python.

## Data Preparation
Data manipulation involved aggregating environmental impact data by various demographic and dietary categories. Transformations included renaming categories for clarity, calculating total impacts, and preparing the data for hierarchical visualization in the treemap and cumulative display in the waterfall charts.

## Repository Contents

Visualization Scripts: Contains all Python scripts used to generate the treemap and waterfall charts.
Data: Includes processed datasets ready for visualization.
Documentation: Additional notes on the data sources, methodology, and detailed comments within scripts explaining the logic and steps taken for data preparation and visualization.
