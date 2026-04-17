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

This visualization shows the number of UFO sightings across different U.S. states. I used a bar chart because it is effective for comparing counts across categorical groups. The x-axis encodes the number of sightings as a quantitative variable, and the y-axis encodes state abbreviations as a nominal variable. I used a sequential blue color scale mapped to the count variable so that higher values stand out more clearly. In the analysis notebook, I cleaned the column names, filtered the data to U.S. observations, grouped by state, and counted the number of sightings. If I had more time, I would normalize sightings by population to make the comparison more meaningful.

---

## Visualization 2: UFO Sightings Over Time by Shape

<iframe src="ufo_plot2.html" width="700" height="500" frameborder="0"></iframe>

This visualization shows how UFO sightings vary over time by reported shape. The x-axis encodes year, while the y-axis or color encoding distinguishes reported shape categories. I used a categorical color scheme because shape is a nominal variable with no natural ordering. For data transformations, I converted the datetime field into timestamps, extracted the year, cleaned the shape labels, and filtered to the most common shapes to keep the chart readable. The interactive element allows the viewer to filter by shape, which makes the chart more useful than a static view because it helps isolate patterns for a single shape rather than showing all categories at once. If I had more time, I would add a geographic filter or a decade slider.
