# Unsupervised learning and dimension reduction

## Datasets

Two different datasets are used in this project:

1. Amazon review dataset with two labels (fake review and nonfake review).
2. Handwritten digit dataset with 10 labels(digit 0-9).

The features of amazon review dataset are text.
The features of hand written digits dataset are numeric.

## Scripts
The scripts are used in jupyter notebook. Some blocks in the middle are only used for test and analysis, you may choose to skip these blocks.

The codes are organized based on the method and data name.

*PCA_reviews.ipynb: k means clustering on amazon review dataset and PCA.
*EM_reviews.ipynb: Expectation maxmimization on amazon reviews.
*ICA_reviews.ipynb: ICA on amazon reviews.
*RS_reviews.ipynb: Randomized selection on amazon reviews.
*FA_reviews.ipynb: Feature Agglomeration on amazon reviews.
*PCA_NN_reviews.ipynb: using PCA to reduce dimension and then fit with neural network. using PCA to reduce dimension, then do clustering and then added cluster info to the feature. Fit with neural network.


*PCA_digits.ipynb: k means clustering on hand written digits dataset and PCA.
*EM_digits.ipynb: Expectation maxmimization on hand written digits.
*ICA_digits.ipynb: ICA on hand written digits.
*RS_digits.ipynb: Randomized selection on hand written digits.
*FA_digits.ipynb: Feature Agglomeration on hand written digits.










