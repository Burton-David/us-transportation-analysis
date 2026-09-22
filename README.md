# Means of Transportation to Work Analysis

An analysis of commuting patterns in the United States using the 2023 American Community Survey (ACS) 5-year estimates dataset.

## Project Overview

This project analyzes transportation modes based on the Bureau of Transportation Statistics dataset, exploring how workers across the United States travel to their workplaces. The analysis covers various transportation modes including:

- Private vehicles (driving alone vs. carpooling)
- Public transportation
- Biking and walking
- Remote work arrangements

## Dataset

The dataset combines commuting data from the 2023 ACS 5-year estimates with Census tract-level geographic boundaries, providing insights into transportation patterns across different regions.

## Directory Structure

```
us-transportation-analysis/
├── README.md
├── blog_post.md              # Write-up of the findings
├── data/
│   └── raw/                  # ACS commuting data (CSV)
├── notebooks/                # The analysis notebook, plus HTML and PDF exports
└── images/                   # Figures the notebook generates
```

## Analysis Highlights

The analysis explores:
1. National-level transportation mode distribution
2. State-by-state comparisons of transportation patterns
3. Transportation mode by population density (tract quartiles, workers per km²)
4. Public transportation usage variations
5. Alternative transportation mode adoption
6. Geographic impacts on transportation choices

## Getting Started

1. Clone this repository
2. Install required dependencies (listed in requirements.txt)
3. Run `notebooks/transportation_analysis.ipynb`

## Visualizations

All visualizations generated during the analysis can be found in the `images/` directory.
