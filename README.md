# WHO Life Expectancy Prediction Project

This repository contains code and documentation for a life expectancy prediction project conducted by the Data Analytics team. The goal of this project is to estimate life expectancies across countries using data provided by the World Health Organization (WHO) between 2000 and 2015. The project includes the construction of two models: one that uses minimal information and another that utilizes more elaborate data for better accuracy.

## Project Overview

 > Data Integrity and Privacy Considerations
The data provided by WHO includes records from 183 countries, but some measurements for life expectancy are missing.
Certain countries have expressed concerns about sharing sensitive data such as medical records, which can have financial implications and hinder social developments.
As ethical data practitioners, features used in the models were carefully selected, taking into account privacy considerations and data integrity.  
 > Model Construction  
 - Minimal Information Model:  
This model uses only the most essential population statistics to make predictions on average life expectancy.  
Features selected for this model do not include sensitive or protected information.  
Suitable for situations where countries are reluctant to share detailed data.  
 - Elaborate Model:  
This model utilizes advanced population data, which may include protected information, to achieve better accuracy in life expectancy predictions.  
Features used in this model may include a broader range of demographic, socioeconomic, and health-related variables.  
The use of this model requires explicit consent from users.  

## Functionality
The repository contains a function that takes relevant population statistics (features) as input and prompts the user to consent to using advanced population data for better accuracy.
Based on the user's response, the function selects the appropriate model (Minimal Information or Elaborate) to make the life expectancy prediction.

## Files in Repository

Life Expectancy Data/: Contains the dataset provided by WHO.  
WHO Dataset - MetaData/: Contains the metadata.
WHO/: Contains scripts for building and training the Minimal Information and Elaborate models.  
WHO_Function/: Contains the function for making life expectancy predictions based on user input.  
README.md: This file providing an overview of the project, its objectives, and instructions for using the provided function.  

## Usage

Clone this repository to your local machine.
Ensure you have the necessary dependencies installed. You may need Python packages such as pandas, scikit-learn, and numpy.
Use the provided function in the functions/ directory to make life expectancy predictions based on relevant population statistics.
Follow the prompts to provide input and consent to the use of advanced population data for better accuracy.

## Conclusion

The life expectancy prediction project addresses the challenge of estimating life expectancies across countries while considering data integrity and privacy concerns. By offering two models with varying levels of information, the project aims to provide flexibility and accommodate different preferences and constraints.
