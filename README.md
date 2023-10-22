# Budweiser US Craft Beers Study

## Overview

Budweiser provided our team with data and asked us to conduct a study on US craft beers and their breweries. In this document, we addressed questions that Budweiser had and reported any interesting findings.  

This repository contains the R Markdown code (Budweiser_US_Craft_Beers_Study.Rmd) and analysis for a study conducted on US craft beers and their breweries. The analysis explores various aspects of craft beers, including their alcoholic content (ABV), bitterness (IBU), and beer styles.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Codebook](#Codebook)
- [Analysis](#analysis)
- [Results](#results)
- [Conclusion](#conclusion)

## How to Use

1. Clone this repository to your local machine.
2. Open and run the R Markdown file (Budweiser_US_Craft_Beers_Study.Rmd) in R or RStudio to reproduce the analysis.

## Introduction

Budweiser provided our team with data and asked us to conduct a study on US craft beers and their breweries. In this document, we addressed questions that Budweiser had and reported any interesting findings.

## Data

The analysis uses two datasets:
- `Beers_updated_2.csv`: Contains information about different craft beers, including ABV, IBU, style, and more. This file is an update from the originally provided data set Beers.csv with some of the missing ABV values populated after research, but it still has the missing IBU values.
- `Breweries.csv`: Provides details about breweries, including their name and location.

Budweiser_US_Craft_Beers_Study.Rmd contains the code for the analysis, including data loading, cleaning, and visualization. You can run the R Markdown file to reproduce the analysis and generate the results.  

## Codebook

### Beers_updated_2.csv

**Variables:**

1. `Name` (Character): The name of the beer.
2. `Beer_ID` (Integer): Unique identifier for each beer.
3. `ABV` (Numeric): Alcohol by Volume (ABV) percentage, indicating the alcoholic content of the beer.
4. `IBU` (Integer): International Bitterness Units (IBU) measure, representing the bitterness of the beer.
5. `Brewery_id` (Integer): The identifier of the brewery that produces the beer.
6. `Style` (Character): The style or type of beer.
7. `Ounces` (Numeric): Ounces of beer.

**Description:**

- `Name` is the name of the beer.
- `Beer_ID` is a unique identifier for each beer in the dataset.
- `ABV` is the Alcohol by Volume (ABV) percentage, showing the alcoholic content of the beer.
- `IBU` represents the International Bitterness Units (IBU) for each beer, quantifying its bitterness.
- `Brewery_id` is the identifier of the brewery that produces the beer.
- `Style` describes the style or type of beer (e.g., Lager, IPA, Stout, etc.).
- `Ounces` is the volume of beer in a fluid ounce.

### Breweries.csv

**Variables:**

1. `Brew_ID` (Integer): Unique identifier for each brewery.
2. `Name` (Character): The name of the brewery.
3. `City` (Character): The city where the brewery is located.
4. `State` (Character): The state in which the brewery is located.

**Description:**

- `Brew_ID` is a unique identifier for each brewery.
- `Name` is the name of the brewery.
- `City` is the city where the brewery is situated.
- `State` represents the state in which the brewery is located.

### Beers_cleaned.csv

This file was exported from the R Markdown file after Beers_updated_2.csv and Breweries.csv were merged, and data were wrangled. This is only for reference and is not required for the R Markdown file. 

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
Author: Katon Pang and Troy McSimov
Date: [10/21/2023]
