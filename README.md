# Anomaly Detection Models for IoT Data.
The goal of this project is to apply anomaly detection models on IoT data in order to find acquisitions that present anomalies, i.e., mistakes in acquiring the data, or unexpected variations of the assesses. We were provided a dataset that contains weather acquisitions of different features, such as ‘rain’, ‘wind’ and ‘temperature’. 

This project was carried out as part of the training of engineers at Tunisia Polytechnic School under the module "Transversal Project" in the third year.

<img src='https://datascience.aero/wp-content/themes/yootheme/cache/AnomalyDetectionData-1-bbb99a40.png' width="50%" eight="50%">

# Approaches.
The most common approach to ensure the quality of sensors’ data, consists in automated detection of erroneous readings or anomalous behaviors of sensors. In the literature, this strategy is known as anomaly detection and can be pursued in many different ways.

In order to solve an anomaly detection problem, we propose these different approaches:

-	**Statistical methods**: These methods use past measurements to approximate a model of the correct behavior of a sensor, where they mark as an anomaly an incompatible result. In this project, the Average Low-High Pass Filter and Seasonal Extreme Studentized Deviate methods were used.
-	**Probabilistic methods**: These methods rely on estimating the probability of the behavior of a sensor, using different well-known distributions, and compare it with a predefined threshold. In this project, the Univariate Gaussian Predictor was used.
-	**Clustering-based methods**: These methods are dependent on calculating the distances between data measurements to distinguish between anomalous and correct readings by assigning the latter to clusters. In this project, the Local Density Cluster-Based Outlier Factor was used.

# Necessary Skills

- Python programming language
- Anomaly detection basics
- Feature engineering
- Machine Learning
