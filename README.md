# Budweiser US Craft Beers Study

## Overview

Budweiser provided our team with data and asked us to conduct a study on US craft beers and their breweries. In this document, we addressed questions that Budweiser had and reported any interesting findings.
This repository contains the R Markdown code (Budweiser_US_Craft_Beers_Study.Rmd) and analysis for a study conducted on US craft beers and their breweries. The analysis explores various aspects of craft beers, including their alcoholic content (ABV), bitterness (IBU), and beer styles.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Analysis](#analysis)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction

Budweiser provided our team with data and asked us to conduct a study on US craft beers and their breweries. In this document, we addressed questions that Budweiser had and reported any interesting findings.

## Data

The analysis uses two datasets:
- `Beers_updated_2.csv`: Contains information about different craft beers, including ABV, IBU, style, and more.
- `Breweries.csv`: Provides details about breweries, including their name and location.

## Analysis

The analysis is divided into several items, including:

1. Number of Breweries by State: A bar chart displaying the number of craft beer breweries in each US state
2. Merging Beer and Brewery Data: Merging beer data with brewery data to associate beers with their respective breweries
3. Handling Missing Values: Addressing missing values in the datasets and imputing missing IBU values
4. **Median ABV and IBU by State**: computing the median alcoholic content and bitterness for each US state and visualizing the results.
5. **Maximum ABV and IBU Beers**: Identifying the states with the maximum alcoholic (ABV) and most bitter (IBU) beers
6. **ABV Distribution**: Analyzing the distribution of alcoholic content (ABV) in the dataset
7. Relationship between ABV and IBU: Investigating the relationship between the bitterness of beer and its alcoholic content
8. Comparison of IPAs and Other Ales: Exploring the Differences in ABV and IBU between India Pale Ales (IPAs) and Other Types of Ale

## Results

The results of the analysis are presented with visualizations and explanations, including the number of breweries by state, merged data samples, handling of missing values, and more. Notable findings include the states with the highest ABV and IBU beers, the distribution of ABV and IBU, and the relationship between these two factors.

## Additional Analysis

The repository also includes additional data analysis, such as the distribution of IBU, identifying k values for k-nearest neighbors analysis, and more.

## Conclusion

The analysis provides insights into the world of US craft beers, their characteristics, and their distribution across states. The findings are summarized in the R Markdown document.

For a detailed walkthrough of the analysis, please refer to the R Markdown document.

---
Author: Katon Pang
Date: [10/21/2023]



This repository contains an R Markdown file (Budweiser_US_Craft_Beers_Study.Rmd) that analyzes and visualizes data related to US craft beers. The analysis uses two datasets: Beers_updated_2.csv and Breweries.csv.

## Analysis

The R Markdown file (Budweiser_US_Craft_Beers_Study.Rmd) contains the code for the analysis, including data loading, cleaning, and visualization. You can run the R Markdown file to reproduce the analysis and generate the results.

## Datasets

The analysis uses two datasets:

1. **Beers_updated_2.csv**: This dataset contains information about different beers, including their names, breweries, styles, IBU (International Bitterness Units), and ABV (Alcohol by Volume).

2. **Breweries.csv**: This dataset provides information about the breweries, including their names, cities, and states.

## How to Use

1. Clone this repository to your local machine.
2. Open and run the R Markdown file (Budweiser_US_Craft_Beers_Study.Rmd) in R or RStudio to reproduce the analysis.

## Codebook

### Beers_updated_2.csv

**Variables:**

1. `beer_id` (Integer): Unique identifier for each beer.
2. `name` (Character): The name of the beer.
3. `brewery_id` (Integer): The identifier of the brewery that produces the beer.
4. `state` (Character): The state in which the brewery is located.
5. `style` (Character): The style or type of beer.
6. `ibu` (Numeric): International Bitterness Units (IBU) measure, representing the bitterness of the beer.
7. `abv` (Numeric): Alcohol by Volume (ABV) percentage, indicating the alcoholic content of the beer.

**Description:**

- `beer_id` is a unique identifier for each beer in the dataset.
- `name` is the name of the beer.
- `brewery_id` is the identifier of the brewery that produces the beer.
- `state` is the state in which the brewery is located.
- `style` describes the style or type of beer (e.g., Lager, IPA, Stout, etc.).
- `ibu` represents the International Bitterness Units (IBU) for each beer, quantifying its bitterness.
- `abv` is the Alcohol by Volume (ABV) percentage, showing the alcoholic content of the beer.

### Breweries.csv

**Variables:**

1. `brewery_id` (Integer): Unique identifier for each brewery.
2. `name` (Character): The name of the brewery.
3. `city` (Character): The city where the brewery is located.
4. `state` (Character): The state in which the brewery is located.

**Description:**

- `brewery_id` is a unique identifier for each brewery.
- `name` is the name of the brewery.
- `city` is the city where the brewery is situated.
- `state` represents the state in which the brewery is located.

This codebook provides an explanation of each variable in the datasets used in the analysis, along with a brief description of their meaning and data types. It serves as a reference to understand the data and variables involved in the "Budweiser US Craft Beers Study."
