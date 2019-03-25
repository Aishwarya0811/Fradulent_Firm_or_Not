## Project description:
## Data Set Information:

This dataset is taken from a research explained here.

## Research Paper 
The goal of the research is to help the auditors by building a classification model that can predict the fraudulent firm on the basis the present and historical risk factors. The information about the sectors and the counts of firms are listed respectively as Irrigation (114), Public Health (77), Buildings and Roads (82), Forest (70), Corporate (47), Animal Husbandry (95), Communication (1), Electrical (4), Land (5), Science and Technology (3), Tourism (1), Fisheries (41), Industries (37), Agriculture (200).

## Dataset Information 
There are two csv files to present data.Merged these two datasets into one dataframe. All the steps should be done in Python.Consider Audit_Risk as target columns for regression tasks, and Risk as the target column for classification tasks.

## Attribute Information:

Many risk factors are examined from various areas like past records of audit office, audit-paras, environmental conditions reports, firm reputation summary, on-going issues report, profit-value records, loss-value records, follow-up reports etc. After in-depth interview with the auditors, important risk factors are evaluated and their probability of existence is calculated from the present and past records.

## Relevant Papers:
Hooda, Nishtha, Seema Bawa, and Prashant Singh Rana. 'Fraudulent Firm Classification: A Case Study of an External Audit.' Applied Artificial Intelligence 32.1 (2018): 48-64.

## Preprocess data:

- Explore data, check for missing data and apply data scaling. Justify the type of scaling used.
- Treating outliers was a big task

## Regression Task:
- Applied all the regression models. If your model has a scaling parameter(s) use Grid Search to find the best scaling parameter. Use plots and graphs to help you get a better glimpse of the results.
- Used cross validation to find average training and testing score.
## Regression models: 

- KNN repressor

- linear regression

- Ridge

 - Lasso

- polynomial regression

- SVM both simple and with kernels.

### Best regressor model for this dataset and train your model on the entire dataset using the best parameters and predict buzz for the test_set.

### Classification task:

Decided about a good evaluation strategy and justify your choice.

## Find best parameters for following classification models:

- KNN classifcation

- Logistic Regression

- Linear Support Vector Machine

- Kerenilzed 

- Support Vector Machine

- Decision Tree.

## Which model gives the best results?
