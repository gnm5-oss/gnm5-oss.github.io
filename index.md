---
layout: default
title: IS445 Homework
---

# Illinois Building Inventory Visualizations

[The Data](https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv){: .btn .btn-primary}

[The Analysis](https://github.com/gnm5-oss/gnm5-oss.github.io/blob/main/analysis.ipynb){: .btn .btn-primary}

---

## Visualization 1: Top Agencies by Total Square Footage

<iframe src="plot1.html" width="700" height="500" frameborder="0"></iframe>

This visualization shows the top agencies by total square footage of buildings. I used a bar chart because it is effective for comparing aggregated values across categories. The x-axis represents total square footage (quantitative), while the y-axis represents agencies (categorical). A sequential blue color scale highlights larger totals. The data was grouped by agency and aggregated using sum of square footage. If I had more time, I would normalize by number of buildings and add filtering by agency.

---

## Visualization 2: Building Acquisitions by Usage and Decade

<iframe src="plot2.html" width="700" height="500" frameborder="0"></iframe>

This visualization shows how building acquisitions vary across usage types and decades using a heatmap. The x-axis represents decades, and the y-axis represents usage categories. Color encodes the number of buildings, using a sequential color scale to emphasize higher concentrations. The multiselect filter allows users to focus on specific usage categories, adding interactivity beyond tooltips. Data transformations included grouping years into decades and aggregating counts by usage. If I had more time, I would normalize values and improve labeling clarity.
