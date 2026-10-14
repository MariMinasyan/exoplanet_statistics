# Exoplanet Statistics: Exploratory Data Analysis

A collaborative statistics project exploring data from the NASA Exoplanet Archive. The analysis uses R to summarize exoplanet properties, visualize distributions, and compare selected characteristics across discovery methods.

## Project Overview

The goal of this project is to apply descriptive statistics and exploratory data analysis (EDA) to real astronomical data. We examine the structure and distribution of selected planetary variables, use visualizations to identify patterns, and interpret the results while keeping data limitations in mind.

## Research Focus

The project includes:
- Summarizing numerical variables with descriptive statistics and quantiles.
- Using histograms and boxplots to explore distributions and identify potential outliers.
- Examining Normal Q–Q plots to assess how closely a variable follows a Normal distribution.
- Comparing planetary equilibrium temperature across discovery methods, including Transit, Radial Velocity, and Imaging.
- Interpreting observed patterns without treating descriptive associations as causal relationships.

## Key Findings

The distribution of planetary equilibrium temperature (`pl_eqt`) is right-skewed and does not closely follow a Normal distribution. The analysis also shows differences in observed equilibrium temperatures across discovery methods: planets detected through Imaging tend to have higher temperatures in this dataset, while the Radial Velocity group has a lower median. These comparisons describe the available sample and may reflect selection effects as well as underlying planetary properties.

## Tools and Methods

- **Language:** R
- **Workflow:** R Markdown
- **Methods:** Descriptive statistics, quantiles, histograms, boxplots, Normal Q–Q plots, and grouped comparisons
- **Data source:** NASA Exoplanet Archive dataset included in this repository

## Repository Contents

| File | Description |
|---|---|
| `ExoplanetsDataset.csv` | Dataset used for the analysis |
| `Report.Rmd` | R Markdown source containing the analysis and code |
| `Report.html` | Rendered HTML report |
| `Project1_Final_Report.docx` | Final written project report |

## Reproducing the Analysis

1. Download or clone this repository.
2. Open `Report.Rmd` in RStudio.
3. Make sure the CSV dataset is available in the project directory.
4. Run the R Markdown code chunks in order, or knit the file to render the report.

The analysis is intended to be reproducible using R and the files provided in this repository. If rendering the report in a different environment, check whether any packages referenced in `Report.Rmd` are installed.

## Limitations

This is an exploratory, descriptive analysis. The dataset reflects the planets recorded in the source archive and may contain missing values, uneven group sizes, and observational selection effects. Differences between discovery-method groups should therefore be interpreted cautiously.

## Acknowledgment

This project was completed collaboratively as part of a statistics course. Contributions included data exploration, statistical analysis, visualization, and report preparation.

**Data source:** [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/)
