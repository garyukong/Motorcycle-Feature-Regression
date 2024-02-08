# Predicting Customer Approval of Motorcycles

## Introduction

This project focuses on analyzing key features that influence customer approval of motorcycles, leveraging data from Bikez.com. By exploring the impact of features such as engine responsiveness (torque) and fuel capacity, we aim to provide insights that can guide motorcycle manufacturers in product design to enhance customer satisfaction.

## Goals

- To quantify the impact of motorcycle engine responsiveness and fuel capacity on customer approval.
- To evaluate the predictive power of various motorcycle features on customer approval ratings.
- To assist motorcycle manufacturers in making data-driven decisions regarding product design.

## Dataset

The dataset includes specifications for 38,472 motorcycles, sourced from Bikez.com. It features 28 unique attributes for each motorcycle, including brand, model, and year, with the main variables of interest being torque and fuel capacity.

### Source:
- Bikez.com, accessed on 30 April 2022.

## Methodology

1. **Data Preprocessing**: Selection and cleaning of the dataset to focus on motorcycles from the years 2013 to 2022, resulting in 1,135 observations after removing entries with missing values.
2. **Feature Engineering**: Analysis of variables such as torque, fuel capacity, and motorcycle category to define their roles in customer approval.
3. **Model Development**: Construction of regression models to identify significant predictors of customer approval.
4. **Evaluation**: Assessment of model performance through R-squared values and statistical significance of predictors.

## Results

The analysis revealed that torque and fuel capacity significantly affect customer approval ratings. The study also highlighted the importance of motorcycle category in predicting customer approval, with different categories impacting ratings to varying degrees.

## Usage

To replicate the analysis:
1. Clone the repository.
2. Update the filepath in the 
3. Run the analysis notebooks located in the `notebooks/` directory.

## Future Work

Future research could explore the interaction between motorcycle categories and key design features, incorporate simplified versions of currently excluded categorical variables, and utilize additional datasets like sales data for a more comprehensive understanding of motorcycle success factors.

## Project Organization

    ├── LICENSE
    ├── README.md          
    ├── data
    │   ├── raw            <- Original Bikez.com data used for analysis.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   └── processed      <- The final, canonical data sets for modeling.
    ├── notebooks          <- .Rmd notebooks. 
    └── reports            <- Generated analysis as PDF and latex format.
