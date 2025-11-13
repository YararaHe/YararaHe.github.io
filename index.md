---
layout: default
title: UFO Altair Visualizations
---

# Visualization 1: UFO Reports per Year

<iframe src="plot1.html" width="800" height="400"></iframe>

## Write-up
This chart shows how many UFO sightings were reported each year.
I used a line chart where the x-axis encodes the year and the y-axis encodes the number of reports.
I parsed the date_time column using pandas and grouped counts by year.

---

# Visualization 2: Interactive Map of UFO Sightings

<iframe src="plot2.html" width="800" height="450"></iframe>

## Write-up
This map shows the spatial locations of UFO sightings using latitude and longitude.
Each point is colored by the UFO shape.
I filtered the data to include sightings from 2000 onward and removed missing coordinates.

## Interactivity Discussion
This visualization includes a dropdown menu that allows users to filter sightings by UFO shape.
This makes the map clearer and reduces overplotting.

---

# The Data
[Click to view dataset](https://github.com/UIUC-iSchool-DataViz/is445_data/raw/main/ufo-scrubbed-geocoded-time-standardized-00.csv)

# The Analysis
[Click to view notebook](ufo_viz.ipynb)
