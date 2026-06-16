# Stochastic Cyclone Tracking & Atmospheric Motion Vector Estimation
![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![PowerBI](https://img.shields.io/badge/PowerBI-Dashboard-yellow.svg)
![DeepLearning](https://img.shields.io/badge/Deep%20Learning-CNN%20%7C%20Encoder--Decoder-orange.svg)
![IEEE](https://img.shields.io/badge/Published_in-IEEE_TGRS-blue)

This repository serves as a research showcase for the study of tropical cyclones, combining advanced stochastic modeling, deep learning architectures, and data visualization techniques.

This research was conducted as part of postgraduate studies at the Indian Institute of Space Science and Technology (IIST).

## 📚 Publications
The methodologies and findings associated with this project have been peer-reviewed and published in the following journals and conferences:

IEEE Transactions on Geoscience and Remote Sensing (TGRS): [[Paper]](https://ieeexplore.ieee.org/document/8548596) - "Consistent Robust and Recursive Estimation of Atmospheric Motion Vectors From Satellite Images" (2019).

Springer CVIP 2017: [[Paper](https://www.researchgate.net/publication/324449464_Stochastic_Assimilation_Technique_for_Cloud_Motion_Analysis)] - "Stochastic Assimilation Technique for Cloud Motion Analysis" (2018).

## 📊 1. Data Visualization & Insights (Power BI)
An interactive Power BI dashboard serves as the front-end for exploring spatial and temporal trends in cyclone data. This allows users to quickly gain insights into cyclone frequency, intensity, and geographical paths.

*  **Data Sources:** 
Integrates historical data from the global IBTrACS repository with near-real-time updates collected from the official Indian space portal MOSDAC (mosdac.gov.in).
*  **Features:**
Real-time reporting, storm trajectory tracking, and intensity classification.

<img width="1000" alt="Power BI Dashboard" src="https://github.com/user-attachments/assets/7d01f726-96b3-490d-9e47-c6d3f1ef4d64" />

## 🧠 2. Deep Learning & Stochastic Modeling
This phase of the project focuses on automating feature extraction and the precise estimation of Atmospheric Motion Vectors (AMVs) to improve prediction accuracy in highly stochastic weather environments.

* **Stochastic Modeling:**
Proposed a modified Weighted Ensemble Transform Kalman Filter (mWETKF) for robust motion vector estimation.

<img width="1128" height="456" alt="Screenshot 2026-06-16 060952" src="https://github.com/user-attachments/assets/d9c2b792-9b3c-41ad-a134-31b84ff7541f" />

* **Architectural Research:**
Evaluated supervised CNNs and Unsupervised Encoder-Decoders to replace traditional Numerical Weather Prediction (NWP) models with spectral-domain operations to reduce computational latency.

