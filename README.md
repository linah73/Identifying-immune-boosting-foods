
 Summary:
 
 Developed a model to classify grocery food items based on their immune-boosting properties.
▪ Employed Random Forest classification algorithm and feature importance permutation method to determine the
relative micronutrient contribution to immunity strength.
▪ Assembled the dataset by wrangling data from 100+ data files collected from the CDC National Health and
Nutrition Examination Survey website.
▪ Developed a scoring system based on the weighted importance of the micronutrients to score grocery foods in the
USDA nutrition dataset.


The repository contains the four notebooks which can be run in this order:

"Capstone2_DataCleaning.ipynb.ipynb" contains data cleaning and wrangling code, data source and the variable definitions

"Capstone2_EDA.ipynb" contains code for exploratory data analysis

"Capstone2_model-final.ipynb" contains model training, evaluation and the final model metrics

"Capstone2_Food_Scoring_function.ipynb" contains the function used to rate foods and the visialization 

The "NHANES_merged.csv" file is the data file containing assembled data from the collected data tables

The "NHANES_final.xlsx" is the cleaned data file with imputed missing values

The file "Nutritions_US.csv" contains the original dataset of foods and nutritional info downloaded from USDA data 

The file "feature_importance_values.csv" containts the calculated feature importance values 

The project report is saved in the file "Capstone 2 Project report.pdf"

The presentation is saved in the file "Capstone2_Presentation.pdf"
