# INFO 4310 — Final Project Report

## Overview

This repository contains the final project for INFO 4310, which aims to inform users about the 2024 Atlantic hurricane season by following Hurricane Katrina’s path. The project provides an in-depth, interactive analysis to educate and inform the public about the potential severity of the upcoming hurricane season, the science behind hurricanes, and the impact of climate change on their intensity and frequency.

## Online Version

You can view the online version of the project [here](https://jgreene114.github.io/INFO4310-FP/index.html).

## Goals and Motivation

The primary goal of this project is to educate and inform the public about:
- The science behind hurricane formation.
- Variables that make hurricanes more likely to occur and intensify.
- The potential severity of the 2024 Atlantic hurricane season.
- The impact of climate change on hurricane intensity and frequency.

## Intended Use Case

### Audience
- General public interested in climate change and natural disasters.
- Researchers and meteorologists studying hurricane patterns.
- Policy makers and emergency response teams preparing for hurricane seasons.

### Use Cases
- **Education**: Informing the public about hurricane formation, impacts, and safety measures.
- **Research**: Providing a detailed case study of Hurricane Katrina to compare with future hurricanes.
- **Preparation**: Helping policy makers and emergency responders plan and prepare for the upcoming hurricane season.

## Related Materials

### Inspiration
- **Map Visualization of Hurricane Katrina**: Inspired by the New York Times article, "The Great Flood of 2019: A Complete Picture of a Slow-Motion Disaster."
- **Bubble Chart of Billion-Dollar Natural Disasters**: Inspired by the New York Times article, "The Cost of Hurricane Harvey: Only One Recent Storm Comes Close."
- **Line Plots of Sea Surface Temperatures and Ocean Heat Content**: Inspired by the University of Miami's article on "Ocean Heat Content."
- **Oceanic Niño Index (ONI) Graph**: Inspired by the National Oceanic and Atmospheric Administration’s report on El Niño/Southern Oscillation.

## Data Sources and Processing

### Data Sources
- **Hurricane Katrina Map**: International Best Track Archive for Climate Stewardship (IBTrACS)
- **Niño Regions Sea Surface Temperatures (1982-2024) Line Plot**: National Oceanic and Atmospheric Administration (NOAA)
- **Ocean Heat Content in Main Development Region Line Plot**: University of Miami
- **Bubble Chart of Billion-Dollar Natural Disasters**: NOAA’s report on Billion-Dollar Weather and Climate Disasters

### Data Processing
- **Niño Regions Sea Surface Temperatures (1982-2024) Line Plot**: Cleaned and averaged temperature values, standardized month and year, removed unnecessary columns.
- **Ocean Heat Content in Main Development Region Line Plot**: No additional processing required.
- **Bubble Chart of Billion-Dollar Natural Disasters**: Processed event dates, converted costs to billions, cleaned event descriptions.

## Process and Other Designs Considered

- Initial ideas included 3-panel pages and scraping Wikipedia for hurricane overviews.
- Focused on visual elements and scroll-triggered transitions using GreenSock (GSAP).
- Feedback led to a more scoped and focused project.

## Final Design

### Visual Channels
- Size indicates intensity (e.g., map and bubble chart).
- Color transitions show value changes (e.g., wind speed and SSHS value).

### Implementation
- **Niño Regions Sea Surface Temperatures Line Plot**: Visualizes temperature trends and anomalies over time with interactive tooltips.
- **Oceanic Niño Index (ONI) Bar Chart**: Emphasizes temperature anomalies with dual Y-axes and interactive elements.
- **Ocean Heat Content in MDR Line Plot**: Focuses on heat content trends in the Main Development Region.
- **Bubble Chart of Billion-Dollar Natural Disasters**: Visualizes economic impact of extreme weather events with interactive tooltips.
- **Katrina Storm Path Map**: Interactive map showing Hurricane Katrina's path, with information layers for user interaction.
