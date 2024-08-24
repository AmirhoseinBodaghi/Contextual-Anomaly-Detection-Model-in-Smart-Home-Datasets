Contextual Anomaly Detection in Smart Home Datasets:
This repository contains two primary Jupyter notebooks: 1- SyntheticDataGeneration.ipynb and 2- GraphBasedAnomalyDetection.ipynb. The first notebook generates synthetic smart home data, while the second applies a graph-based anomaly detection method to the generated data.

Overview of the Notebooks:

SyntheticDataGeneration.ipynb:
In this notebook, we take an existing real-world smart home dataset as input and generate a synthetic dataset that closely replicates its characteristics. A conformance test is then performed to ensure that the synthetic data accurately reflects the properties of the original dataset.


GraphBasedAnomalyDetection.ipynb:
This notebook implements a graph-based anomaly detection technique on the synthetic dataset created in the first notebook. To evaluate the effectiveness of the method, we introduce synthetic anomalies into the dataset. The detection performance is assessed using several models, including Isolation Forest (IF), Local Outlier Factor (LOF), Mahalanobis Distance (MD), and One-Class Support Vector Machine (OCSVM).
