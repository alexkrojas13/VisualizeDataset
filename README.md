#How to Best Visualize a Dataset Easily

#Overview

The human activities dataset contains 5 classes (sitting-down, standing-up, standing, walking, and sitting) collected on 8 hours of activities of 4 healthy subjects. The data set is downloaded from [here](http://groupware.les.inf.puc-rio.br/har#ixzz4Mt0Teae2). This code downloads the dataset, cleans it, creates feature vectors, then uses [T-SNE](https://lvdmaaten.github.io/tsne/) to reduce the dimensionality of the feature vectors to just 2. Then, we use matplotlib to visualize the data. 

##Dependencies

* pandas(http://pandas.pydata.org/) 
* numpy (http://www.numpy.org/) 
* scikit-learn (http://scikit-learn.org/) 
* matplotlib (http://matplotlib.org/) 

Install dependencies via '[pip](https://pypi.python.org/pypi/pip) install'. (i.e pip install pandas). 

Note** updated dataset is here if the other link is broken
http://rstudio-pubs-static.s3.amazonaws.com/19668_2a08e88c36ab4b47876a589bb1d61c37.html﻿

##Usage

To run this code, just run the following in terminal: 

`python data_visualization.py`
