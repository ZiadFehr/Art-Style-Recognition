# Art-Style-Recognition
This is a simple Art Syle Recoginition model. The model uses Scikit's K-Means Clustering, but it was tested on Agglomerative Clustering prior only to yield slightly better results with a considerably higher inference time.
Due to the nature of the model being Unsupervised Learning, the only metric used to evaluate it with is the Silhouette Score. The dataset that is used to train and validate this model is too large to be uploaded here, but it
can be found [here](https://www.kaggle.com/datasets/thedownhill/art-images-drawings-painting-sculpture-engraving/data) (It can also be found as a comment in main). The dateset has been stripped down to ignore the musemart folder.
