# Information-Retrieval

## Dataset creation

The data we used is a collection about different U.S. presidential debates from 2016 and 2020. For each statement and answer summarization is performed. The scipt IR_summary.ipynb can be used to build a dataset

## Models

All models which were used, can be found in the file Models. The name "sum_raw" indicates that these models are trained using summary of statements/answers and the original data, while "raw" means just the original data was used

## Training / Analysis

The file IR.ipynb contains the notebookm to perform the training and testing. It is important to take into account, that through the small dataset size results may variate partly. Therefore it can be necessary to train several times the classifier. This file also includes the script fore the analysis of the results
