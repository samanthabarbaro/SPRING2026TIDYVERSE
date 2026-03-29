# SPRING2026TIDYVERSE

This repository contains examples of data analysis and visualization using TidyVerse packages in R, created as part of the SPRING 2026 course assignments.

## UFO Sightings Analysis

### Dataset
The UFO sightings dataset is publicly available and included in this repository:

- **File:** `UFO sighting.csv`  
- **Source:** Kaggle / publicly shared dataset  
- **Description:** Contains observations of UFO sightings worldwide, including date/time, city, state, country, reported shape, duration, and comments.

### Vignette
A full example vignette demonstrating TidyVerse capabilities is included:

- **File:** `TidyVerse CREATE assignment.qmd`  
- **Objective:** Clean, summarize, and visualize UFO sightings by country, year, and reported shapes to uncover trends and patterns.  
- **Packages Used:**  
  - `dplyr` – Data manipulation (filtering, summarizing, grouping)  
  - `tidyr` – Data tidying (handling missing values, cleaning data)  
  - `ggplot2` – Data visualization (bar plots, line plots, multi-color charts)  

### Highlights
- Rows with missing or `"NULL"` values were cleaned or replaced with `"Unavailable"` for accurate summaries.  
- Sightings are analyzed by **country**, **year**, and **UFO shape**.  
- Visualizations include:
  - Top 10 countries by UFO sightings  
  - Top 10 reported UFO shapes with multi-color bar charts  

### How to Run
1. Install TidyVerse package if not already installed:

```r
install.packages("tidyverse")
## Student Examples

### Theresa Benny
**Title:** Analyzing Student Burnout Using dplyr  
**File:** `Analyzing Student Burnout using dplyr.Rmd`  
**Dataset:** Student Mental Health and Burnout (Kaggle)  

This example demonstrates how to use dplyr to analyze the relationship between academic pressure and burnout. The analysis shows that burnout levels remain relatively consistent across different levels of academic pressure, highlighting the importance of validating assumptions with data.
# kristoffgit
* added tidyverse create assignment that includes filter and select msleep code
## Sinem K Moschos – Airline Passenger Satisfaction Vignette

This vignette uses the Kaggle Airline Passenger Satisfaction dataset to demonstrate Tidyverse functions.

### Dataset
Airline Passenger Satisfaction dataset from Kaggle
Link: `https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction`

### Tidyverse functions used
- `select()`
- `mutate()`
- `group_by()`
- `summarise()`
- `ggplot()`

### Summary
In this example, I compared satisfaction rates between business travelers and personal travelers. I first selected the relevant columns, then created a logical satisfaction variable, grouped the data by type of travel, and calculated the satisfaction rate for each group. Finally, I visualized the results with a bar chart.

### File
- `airline_vignette.R`
