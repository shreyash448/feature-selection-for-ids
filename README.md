README
Overview
This Jupyter notebook (idsColl.ipynb) provides a detailed analysis of the UNSW-NB15 dataset and implements a multilayered feature selection process for an intrusion detection system (IDS). The notebook leverages Pearson correlation for feature selection and presents experimental results using a Decision Tree model.

In the feature selection method first we correlate between the features to remove those feature which are highly correlated (using pearson correlation) , then in the second step we correlate remaing features with the label of the dataset and select the top 15 correlated features.
