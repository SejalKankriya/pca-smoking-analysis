# PCA Analysis of UK Smoking Data
This project employs Principal Component Analysis (PCA) to explore the demographic and socioeconomic factors influencing smoking habits across various populations in the UK.

<img src="https://github.com/SejalKankriya/pca-smoking-analysis/assets/43418191/4bdc934d-2214-42de-8fae-de2ef01144a1" width="50%" height="50%">

## Project Overview

Using a dataset sourced from the National STEM Centre and available through OpenIntro, this project delves into the characteristics of smokers based on multiple variables, such as age, gender, income level, and education. The main goal is to understand underlying patterns that may not be immediately obvious from straightforward analysis techniques.

## Data Description

The dataset comprises 1,691 observations with the following key variables:

  * Gender: Male or Female
  * Age: Continuous variable representing the age of the respondents
  * Marital Status: Includes categories such as Married, Single, Divorced, etc.
  * Income: Ranges from under 2,600 to above 36,400
  * Education: Levels from No Qualification to Degree and higher
  * Smoking Status: Smoker or Non-Smoker

## Analytical Approach

The analysis process is divided into several key steps:

  * **Data Cleaning:** Simplifying the dataset by focusing on relevant variables and omitting incomplete records.
  * **Variable Transformation:** Converting categorical data into numeric formats suitable for PCA.
  * **PCA Execution:** Running PCA to reduce dimensionality and identify principal components that capture significant variance.
  * **Visualization:** Generating biplots and scree plots to visualize the outcomes of the PCA.

## Repository Structure

  * **smoking.R:** R script for loading and preprocessing the data.
  * **PCA.Rmd:** R Markdown document that details the PCA process and findings.
  * **Smoking_Patterns_PCA_Overview.pdf:** Compiled analysis report from the R Markdown file.

## Results
Initial findings suggest distinct demographic profiles between smokers and non-smokers, influenced by factors like marital status and education level. These insights are visualized through biplots, highlighting the variance explained by the principal components.

<img src="https://github.com/SejalKankriya/pca-smoking-analysis/assets/43418191/2c553ce5-4a3c-45d3-b5b4-8302a946f093" width="50%" height="50%">

## How to Use This Repository
To explore the analysis:

  * Clone the repository.
  * Run the smoking.R script to load the data.
  * Review the PCA.Rmd for detailed methodology and insights.
  * Open PCA_Analysis_Output.pdf for a comprehensive report of the findings.

## License
This repository is licensed under the MIT License
