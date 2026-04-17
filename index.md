---
layout: default
title: IS445 Homework 5
---

# UFO Sightings Visualizations

[The Data](https://github.com/UIUC-iSchool-DataViz/is445_data/raw/main/ufo-scrubbed-geocoded-time-standardized-00.csv){: .btn .btn-primary}

[The Analysis](https://github.com/gnm5-oss/gnm5-oss.github.io/blob/main/analysis.ipynb){: .btn .btn-primary}

---

## Visualization 1: UFO Sightings by State

<iframe src="ufo_plot1.html" width="700" height="500" frameborder="0"></iframe>

This visualization shows the number of UFO sightings across different U.S. states. A bar chart was used because it is effective for comparing categorical data. The x-axis represents the number of sightings, and the y-axis represents states. A sequential blue color scale highlights higher counts. The data was grouped by state and aggregated using counts. If I had more time, I would normalize by population and explore regional differences.

---

## Visualization 2: UFO Sightings Over Time by Shape

<iframe src="ufo_plot2.html" width="700" height="500" frameborder="0"></iframe>

This visualization shows how UFO sightings vary over time by reported shape. The x-axis represents time, while color encodes shape categories. The interactive dropdown allows users to filter by shape, making the visualization more clear and focused beyond basic tooltip functionality. Data transformations included converting date fields to timestamps and filtering to the most common shapes. If I had more time, I would add geographic filters and improve temporal aggregation.
