---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Evaluating the Effects of Acid Fracture Etching Patterns on Conductivity Estimation
  Using Machine Learning Techniques
subtitle: ''
summary: ''
authors:
- Mahmoud Desouky
- Murtada Saleh Aljawad
- Hamed Alhoori
- Dhafer Al-Shehri
tags:
- '"machine learning"'
- '"Petroleum Engineering"'
categories: []
date: '2020-06-01'
lastmod: 2020-10-10T14:08:12-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-10-10T19:08:12.249064Z'
publication_types:
- '1'
abstract: The successful design of an acid fracture job requires accurate prediction
  of fractured well productivity. Productivity estimation demands knowledge of both
  the acid penetration length and conductivity distribution for the given reservoir.
  The literature includes several models developed to predict the conductivity of
  acid fractured rock. The most popular is empirical and based on measuring the conductivity
  of 25 acid fracture experiments. The present research provides empirical models
  utilizing machine learning techniques and incorporating 97 experiments and 563 datapoints.
  We conducted an extensive literature review to collect the published data on acid
  fracture experiments. The objective of such experiments is to measure conductivity
  at different formation closure stresses while considering field conditions. We used
  several data preprocessing techniques to clean the data, fill in missing values,
  exclude outliers and failed experiments, and standardize the dataset. Regularization
  was employed to eliminate features that didn't contribute to accurate prediction.
  Feature engineering was used to construct new features from our dataset. We began
  by measuring the correlations between features to better understand the data. We
  then built various machine learning models to predict acid fracture conductivity.
  It has been observed that developing one universal empirical correlation often results
  in significant errors in conductivity estimation because different rock types result
  in different etching patterns that cannot be explained by a single correlation.
  For instance, the channeling etching pattern is mostly observed in limestone formations,
  while a roughness pattern is seen in dolomite and chalk rock. Moreover, the conductivities
  of etching patterns formed in chalk, dolomite, and limestone formations behave differently.
  We built machine learning classification techniques to determine the most likely
  etching patterns (e.g., channeling, roughness). A linear regression-based model
  was then developed as a baseline for comparison with other models generated through
  ridge regression. We evaluated the performances of our models using well-known metrics
  such as accuracy, precision, recall, mean squared error, and correlation coefficients.
  We also employed cross-validation to avoid over-fitting, finding that certain features
  were the most important in predicting acid fracture conductivity. Detailed empirical
  conductivity correlations and models were developed in this work for three carbonate
  rock types. Previously, a single empirical model has often been employed to estimate
  acid fracture conductivity or, at best, a model has been developed for a particular
  rock type. Most models have not considered the impact of etching patterns on conductivity,
  which was found to be significant in limestone.
publication: '*SPE Europec featured at 82nd EAGE Conference and Exhibition*'
url_pdf: publications/desouky-2020-spe.pdf
doi: 10.2118/200527-MS
---
