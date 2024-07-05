# Anomaly Detection in Honey Bee Colony Data using DBSCAN

## Project Overview
This project focuses on detecting anomalies in honey bee colony data using the DBSCAN (Density-Based Spatial Clustering of Applications with Noise) algorithm. The data is sourced from a citizen science project involving 78 honey bee colonies in Germany. Each hive was equipped with multiple sensors to monitor various environmental parameters and hive conditions.

## Data Sources
* Dataset Link: Zenodo Dataset(https://zenodo.org/records/10407693)
* Research Paper: (https://www.sciencedirect.com/science/article/pii/S2352340923010429?via%3Dihub)

## Data Description
The original dataset includes many features, but for simplicity, we selected the following key features for anomaly detection:

* t_i_1 to t_i_5: Temperature sensors inside the hive, with t_i_3 at the center and t_i_1 and t_i_5 at the margins.
* t_o: Outside temperature.
* weight_kg: Overall hive weight.
* h: Relative humidity.
* t: Temperature inside the hive.
* p: Air pressure.


## Anomaly Detection using DBSCAN
The DBSCAN algorithm was applied to the selected features to detect anomalies. Data preprocessing involved imputing missing values and normalizing the data to ensure suitability for clustering.


For further details on the dataset and the study, please refer to the dataset and the research paper linked above.