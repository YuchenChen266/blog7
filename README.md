# Blog 7: Interactive Plotly Visualization: Wages and Unemployment Across U.S. States
This repository contains the R Markdown code for an interactive Plotly visualization.
The analysis explores the relationship between median wage and unemployment rate across simulated U.S. states, comparing patterns across three industry sectors.

## Repository Structure
- `blog7.Rmd`: R Markdown source file, including text and reproducible analysis code
- `blog7.html`: Rendered webpage published via GitHub Pages

## Replication Instructions
1. Open `blog7.Rmd` in RStudio.
2. Install required packages:
install.packages(c("plotly","dplyr"))
3. Knit the document to generate the rendered blog7.html page and interactive figure.

All observations are simulated state-level data generated programmatically within the R code. No external CSV data files are required.
The interactive visualization uses a dropdown menu to switch between industry groups, with hover tooltips to view individual state information.
