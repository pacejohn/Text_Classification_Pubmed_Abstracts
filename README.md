Text Classification of Pubmed Abstracts

This repo includes Jupyter Notebooks that demonstrate how to do text classification of Pubmed abstracts using Logistic Regression, Random Forests, and XGBoost.  Default hyperparameters were used since this is just to show how to perform the classifications.

Logistic Regression classifier for abstracts from Pubmed (https://pubmed.ncbi.nlm.nih.gov/).  2000 abstracts from 5 categories were downloaded.  The category name was entered in the search box and the first 2000 abstracts were saved.  Some abstracts are not very good examples of the category, but this helps since it is more realistic.The abstracts were saved in "Pubmed" file format and had to be parsed to extract just the abstract from each record.  Parsed files are zipped.

The categories are:
 -Dental caries
 -Dental pulp
 -Periodontal disease
 -Endodontic treatment
 -Transposable elements

Abstracts were preprocessed, then TF-IDF vectors were created to use as input.  Other vectorization could be used.  Mostly default hyperparameters were used in order to demonstrate how to do classification.  Try using grid search to see if you can get better accuracy results.

Last updated 12/4/20.
