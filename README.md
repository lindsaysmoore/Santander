# Santander
Kaggle Santander challenge notebooks
From kaggle: "In this competition, Santander Group is asking Kagglers to help them identify the value of transactions for each potential customer. This is a first step that Santander needs to nail in order to personalize their services at scale."

To do this, they have provided us with 4459 known transaction values and 4991 features for each of those values. The features are anonymized, so we don't actually know what any of them represent. The most striking thing about these data are that the matrix is very sparse. There are very many zero counts. To me this automatically points to a need to do a PCA to rotate the axis to get better variables. 

## Requirements:
I'm using Anaconda 3 with Python 3.6.  
You'll need:  
- pandas
- numpy
- matplotlib
- seaborn
