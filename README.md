# Statistical Data Visualization in R

This repository contains a comprehensive analysis of US county data using various statistical visualization techniques in R.

## Project Overview

This project demonstrates how to use different types of graphical displays to explore and analyze data from the `usdata` package's county dataset. The visualizations include:

1. **Histograms** - Examining the distribution of unemployment rates across US counties
2. **Boxplots (by State)** - Comparing median household income across five randomly selected states
3. **Boxplots (by Education Level)** - Analyzing how poverty rates relate to educational attainment
4. **Scatterplots** - Exploring the relationship between unemployment and poverty rates

## Dataset

The analysis uses the `county` dataset from the `usdata` package, which contains demographic and socioeconomic information about US counties, including:
- Population data
- Poverty rates
- Education levels
- Unemployment statistics
- Income metrics
- And more

## Key Findings

### Unemployment Rate Distribution
- The histogram reveals a slight positive skew in unemployment rates across US counties
- Most counties cluster around the average, with some outliers showing higher unemployment
- Right skew reflects economic realities: unemployment has a lower bound (0%) but no upper bound

### Median Household Income by State
- Significant economic differences exist between states
- Income patterns vary with some states showing high values and broad distributions
- Outliers often represent affluent counties near major cities or isolated poor rural areas
- Interquartile range in boxplots illustrates income inequality within states

### Poverty Rates by Education Level
- Strong negative correlation between education and poverty
- Counties with bachelor-degree educated populations show substantially lower poverty rates
- Education correlates with better employment opportunities, higher wages, job security, and economic adaptability
- Higher education leads to professional/managerial positions and better industry participation

### Unemployment-Poverty Relationship
- Scatterplot demonstrates significant positive correlation (0.55) between unemployment and poverty
- Higher unemployment consistently associates with higher poverty rates
- Economic factors creating this relationship:
  - Income loss during unemployment leading to poverty
  - Regional economic issues affecting both unemployment and poverty
  - Structural problems undermining education, economic activity, and development
  - Poverty reducing local spending, which further increases unemployment

## Files in this Repository

- `STAT311-HW2-Writeup.Rmd`: R Markdown file containing code and analysis
- `STAT311-HW2.pdf`: PDF output with all visualizations and written analysis

## Requirements

To run this code, you will need:
- R (version 4.0 or higher recommended)
- The `usdata` package

## Installation

```R
# Install the required package
install.packages("usdata")

# Load the library
library(usdata)
```

## Usage

You can open and run the R Markdown file in RStudio for a complete interactive experience:

```R
# In RStudio
install.packages("rmarkdown")
rmarkdown::render("STAT311-HW2-Writeup.Rmd")
```

## Why This Analysis Matters

These visualizations demonstrate fundamental statistical concepts:

- **Histograms** reveal the shape, central tendency, and spread of data distributions
- **Boxplots** allow for effective comparison between groups, highlighting median differences and identifying outliers
- **Scatterplots** reveal relationships between variables, helping to identify patterns and correlations

The educational-economic relationships highlighted in this analysis also provide valuable insights into socioeconomic factors affecting US counties.
