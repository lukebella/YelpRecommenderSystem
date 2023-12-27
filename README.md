# YelpRecommenderSystem

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lukebella/YelpRecommenderSystem/blob/master/yelp_recommender.ipynb)
![Python Version from PEP 621 TOML](https://img.shields.io/python/required-version-toml?tomlFilePath=https%3A%2F%2Fraw.githubusercontent.com%2Flukebella%2FYelpRecommenderSystem%2Fmain%2Fpyproject.toml)

This work focuses on recommending businesses to an user retrieved
from [Yelp Dataset](https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset). The first part focuses on manipulating data to
calculate the review rating in a more clever way. The collaborative filtering
based on user similarity was later implemented. In the final section the UV
decomposition phase was carried out: the performance of this dimensional
reduction approach (written from scratch) was compared with that of the
spark.mllib.ALS through training and testing phases.

## Features

* Basic Recommendation
* Collaborative Filtering
* UV Decomposition
* ALS


## Developers

* [Bellani Luca](https://github.com/lukebella)
* [Longoni Andrea](https://github.com/Andreal2000)
