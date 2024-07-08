# UCAmI-Contextual-Anomaly-Detection
This repo, has two codes: 1- SyntheticDataGeneration.ipynb , and 2- GraphBasedAnomalyDetection.ipynb, the first code create a synthetic smart home and the second code run an anomaly detection on it.

The explanations of the codes:
1- SyntheticDataGeneration.ipynb :
In this code we input a real smart home dataset and create a synthetic dataset that matches that well, and then do a conformance test to make sure it fits well. 
2- GraphBasedAnomalyDetection.ipynb :
In this code we run a graph based anomaly detection method over the synthetic data, and later to evaluate the method, we inject some synthetic anomalies into the synthetic dataset and then try to see how good the method can capture those synthetic anomalies by models (MD, LOF, and IF).
