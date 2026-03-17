# project-for-DSCI441
This project mainly studies the problem of taxi trip type prediction, taking New York City taxi GPS data as the research object. 
# NYC Taxi Trip Duration Classification

## Summary
This project focuses on classifying New York City taxi trips into three categories: short, medium, and long trips. Instead of predicting the exact travel time, the goal is to develop machine learning models that can classify trip durations based on spatial, temporal, and operational features. Accurate trip duration classification can help transportation systems improve dispatch efficiency, estimate travel times, and better understand urban mobility patterns.

The project uses the NYC Taxi Trip Duration dataset and explores how geographic distance, pickup time, and other trip attributes influence trip duration categories.

---

## Methodology
This project follows a standard machine learning workflow including data preprocessing, feature engineering, exploratory data analysis (EDA), and model training.

First, the dataset is cleaned and processed. Temporal features such as pickup hour, weekday, and month are extracted from pickup timestamps. Geographic features are also engineered, including the Euclidean distance between pickup and dropoff locations.

Exploratory data analysis is conducted to understand feature distributions, relationships between variables, and class balance. Visualization techniques such as distribution plots, box plots, violin plots, and correlation heatmaps are used to analyze the data.

Three baseline machine learning models are implemented:

- Decision Tree  
- Gaussian Naive Bayes  
- Multi-Layer Perceptron (MLP)

These models represent interpretable, probabilistic, and neural network approaches to solving the classification problem.

---

## Data Source
The dataset used in this project is the **NYC Taxi Trip Duration dataset** from Kaggle.

Kaggle Competition Page:  
https://www.kaggle.com/c/nyc-taxi-trip-duration


The dataset contains approximately 1.44 million training samples and 618 thousand test samples. Each record includes features such as pickup and dropoff coordinates, timestamps, passenger count, and vendor ID.

---

## References
1. Kaggle NYC Taxi Trip Duration Dataset  
   https://www.kaggle.com/c/nyc-taxi-trip-duration

2. Pedregosa et al. (2011). Scikit-learn: Machine Learning in Python.

3. Géron, A. (2019). Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow.
