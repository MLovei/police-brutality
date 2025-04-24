# Fatal Police Shooting in the United States

## Table of Contents
- [Introduction](#introduction)
- [Project Aim](#project-aim)
- [Technologies](#technologies)
- [Data Source](#data-source)
- [Methodology](#methodology)
- [Key Findings](#key-findings)
- [Future Directions](#future-directions)
- [Installation](#installation)
- [Sources](#sources)

## introduction
This capstone project explores the complex and sensitive topic of fatal police shootings in the United States, analyzing patterns, trends, and contributing factors behind these incidents. Using The Washington Post's comprehensive database of fatal police shootings, this analysis aims to uncover statistical relationships and potential correlations that might inform policy discussions.

## project-aim
To analyze police shooting data in the United States, with a particular focus on examining potential connections between mental health incidents, lunar phases, and other factors that might influence these tragic events.

## technologies
- Python (primary analysis language)
- Jupyter Notebooks
- Data visualization libraries (Matplotlib, Seaborn)
- Statistical analysis tools
- Geocoding utilities
- Clustering algorithms (K-means)

## data-source
The Washington Post's database of fatal police shootings, which has been tracking every fatal shooting in the United States by a police officer in the line of duty since January 1, 2015. This database is considered more reliable than government systems, which have been shown to underreport deaths from legal intervention.

## methodology
### Data Preparation and Cleaning
- Filled missing location data through reverse geocoding
- Created meaningful features including threat level, age group, season, and lunar phase
- Handled potential duplicates and outliers using IQR method

### analysis-techniques
- Applied K-means clustering to identify patterns based on features like age and threat level
- Used chi-squared tests to determine statistical relationships between variables
- Employed various data visualization techniques to explore distributions across categories
- Analyzed temporal trends (yearly, monthly, day-of-week)

## key-findings
- **Lunar Correlation:** The analysis revealed an unexpected correlation between lunar phases and specific incident types, though this likely represents a coincidental statistical pattern rather than causation.
- **Demographic Patterns:** The majority of victims in the dataset were white male adults, though the data also shows significant racial disparities when accounting for population proportions.
- **Temporal Patterns:** Wednesday emerged as the day with the highest number of fatal incidents.
- **Declining Trend:** The data suggests a potential decrease in police shooting incidents over time, which warrants further investigation.
- **Mental Health Factors:** Significant patterns emerged regarding incidents involving individuals with signs of mental illness.

## future-directions
- **Expanded Analysis:** Incorporate additional variables such as officer training, socioeconomic factors, and community policing approaches.
- **Advanced Clustering:** Experiment with alternative clustering methods for potentially deeper insights.
- **Predictive Modeling:** Develop models to identify high-risk situations and inform preventative strategies.
- **Geographic Analysis:** Explore spatial patterns and regional variations in police shooting incidents.

## installation
To run the notebook, first install dependencies using pip:

```
pip install -r requirements.txt
```

## sources
The Jupyter Notebooks in the [src/](src/) folder contain the detailed analysis, code, and visualizations for this project.
