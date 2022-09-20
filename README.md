# Thesis-Exact-AcqFunc-Gradients-BayesOpt-GPs
Thesis chapter (UK version) of journal paper (redacted), US publisher.

Each of the Jupyter notebooks herein should run "out-of-the-box" in Google Colab.

https://research.google.com/colaboratory/faq.html

Runtimes may vary, based upon a combination of your Colab GPU licence (i.e. Colab, Colab Pro, Colab Pro+), the amount of RAM available on your local machine and the strength of your internet connection.

N.B. The notebooks will only work if the datasets from both 1. and 2. (below) are already available in the /content directory of your Google Colab app. You may have to upload 1., using the "Skin_NonSkin.txt" file shown here.

### Real-world applications - datasets ### 

### 1. Skin Segmentation Data Set ### 

Abstract: The Skin Segmentation dataset is constructed over B, G, R color space. Skin and Nonskin dataset is generated using skin textures from face images of diversity of age, gender, and race people.

https://archive.ics.uci.edu/ml/datasets/skin+segmentation#

### 2. California Housing Dataset ###

Abstract: The target variable is the median house value for California districts, expressed in hundreds of thousands of dollars ($100,000).

This dataset was derived from the 1990 U.S. census, using one row per census block group. A block group is the smallest geographical unit for which the U.S. Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people).

A household is a group of people residing within a home. Since the average number of rooms and bedrooms in this dataset are provided per household, these columns may take surpinsingly large values for block groups with few households and many empty houses, such as vacation resorts.

It can be downloaded/loaded using the :func:sklearn.datasets.fetch_california_housing function.

https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html
