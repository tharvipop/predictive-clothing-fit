# Clothing Rating and Fit Prediction Project

### Introduction

In the realm of product recommendation systems, accurately predicting user ratings and clothing fit for personalized products is invaluable. This project explores the creation of predictive systems to enhance user experience and increase sales by suggesting items with high predicted ratings and optimal fit.

### Objective

This project aims to develop and compare various machine learning approaches for predicting clothing ratings and fit. Leveraging interaction data and user/product features, the project delves into models such as linear regression, logistic regression, Jaccardian similarity, and TF-IDF.

### Dataset

The dataset from RentTheRunway, a clothing rental platform, provides features like fit feedback, consumer measurements, review text, ratings, and more. No cleaning was required as the dataset was readily available in JSON format.

### Exploratory Data Analysis

Analyzed fit types and found the need for class weighting due to label imbalance.
Discovered that body type doesn't significantly impact fit prediction.
Explored average ratings across fit types and usage scenarios, revealing the influence of social validation.
Examined ratings over time, revealing stable trends over a 6-year period.

### Methodology

Rating Prediction

Developed rating prediction models starting with a baseline of global average rating.
Utilized user and item features, including exclamation mark count in review text.
Employed interaction data models using Jaccard similarity and user/item biases.

Fit Prediction

Designed fit prediction models, utilizing logistic regression and encoded fit labels.
Leveraged text analysis models (bag-of-words and TF-IDF) on review text.

Results

Rating prediction models' performance varied, with interaction data models generally outperforming plain feature models.
Fit prediction models using text analysis (TF-IDF) demonstrated higher accuracy compared to feature-based models.
Interaction data consistently improved model performance.

### Conclusion

This project showcases the significance of leveraging interaction data and text analysis in improving rating and fit prediction models. It underscores the importance of understanding user sentiment and interaction patterns for accurate predictions and recommendations.
### References

    "A Deep Learning System for Predicting Size and Fit in Fashion E-Commerce," ACM Conference on Recommender Systems (RecSys '19), Abdul-Saboor Sheikh et al., 2019.
    "Decomposing Fit Semantics for Product Size Recommendation in Metric Spaces," Rishabh Misra et al., RecSys, 2018.

### Future Work

While this project focused on existing machine learning models, future research could explore more specialized models tailored for text analysis, regression, and classification. Further investigation into the nuances of user sentiment and interaction patterns could yield even more accurate predictive systems.
