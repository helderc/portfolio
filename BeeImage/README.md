# BeeImages

> **Status: Work in progress**

> Based on DataCamp's Naive Bees project: https://app.datacamp.com/learn/projects/412

The dataset BeeImages (https://www.kaggle.com/datasets/jenny18/honey-bee-annotated-images) was used instead.

Vizualize the Jupyter Notebook here: https://nbviewer.org/github/helderc/portfolio/blob/main/BeeImage/beeimg_hog_pca.ipynb

# Technical information
- Language: Python.
- Features: HOG and Color pixel intensities (vector size of 31296).
- Feature transform: PCA (the best number of components was analyzed).
- Classifier: SVM (linear kernel, binary classification).
- Evaluation: Accuracy, ROC curve and AUC ROC.

