# Latinx STEM Belonging Analysis

This project examines how key student experiences are able to predict a Latinx student’s sense of belonging within a STEM educational setting at a two-year Hispanic-Serving Institution (HSI). Rather than focusing only on academic metrics, this analysis looks at how community, recognition, and validation contribute to belonging for Latinx students in STEM.

## Overview

Survey data was collected from over 450 self-identified Hispanic/Latinx students. The dependent variable used to measure belonging was the survey item:  
**“I am part of the STEM community at [my two-year college]”**

Five predictor variables were selected based on how well they reflect the concepts of community, recognition, and validation. These include whether students spend time on campus outside of class, feel valued by instructors, have STEM conversations with friends or family, and whether their parents influence their career decisions.

A multiple linear regression model was used to determine which of these affective factors significantly predict a student's reported sense of STEM belonging.

## Key Results

- Spending time on campus outside of class and having STEM-related conversations with friends or family were both statistically significant predictors of belonging.
- Instructor-related variables (recognition and understanding) and parental influence were not statistically significant in this model.
- The model explained approximately 16 percent of the variance in Latinx students’ sense of STEM belonging.

## Limitations

This analysis is based on cross-sectional survey data, which means the results show associations but cannot be used to make causal claims. All responses were self-reported, which could introduce bias if students misunderstood a question or answered based on what they thought was expected. Only five predictors were used in the model, so there are likely other meaningful factors that were not accounted for here. The data was also collected from a single two-year Hispanic-Serving Institution, so results may not generalize to students at four-year universities, predominantly white institutions, or other geographic/cultural contexts.

## Project Structure

Latinx-STEM-Belonging/
├── report/
│ ├── Report.Rmd # R Markdown analysis
│ └── Report.html # Knitted HTML version
├── Plots/ # All visualizations
├── .gitignore
├── Latin-STEM-Belonging.Rproj
├── README.md

## Data Privacy

The raw survey data has been excluded from this repository in order to protect student confidentiality. The analysis is fully documented and reproducible with a similar dataset structure.

## View the Report

[Click here to view the full report](https://josephclayton41.github.io/Latinx-STEM-Belonging/)

[LinkedIn](https://www.linkedin.com/in/josephpclayton)
