Hybrid Intrusion Detection System (IDS)
This repository contains the implementation and analysis of a Hybrid Intrusion Detection System (IDS) using machine learning algorithms and the CIC-IDS-2018 dataset. The project aims to detect and classify various network intrusion scenarios with high accuracy and adaptability.

Table of Contents
Introduction
Dataset
Algorithms and Techniques
Results Summary
Installation
Usage
File Structure
Contributions
License
Introduction
This project focuses on developing a Hybrid IDS by leveraging Network-based IDS (NIDS) and Host-based IDS (HIDS) to detect intrusions effectively. It combines advanced machine learning models, real-time data handling capabilities, and ensemble techniques to classify network activities as normal or malicious.

Dataset
The project uses the CIC-IDS-2018 dataset, which includes diverse attack scenarios such as:

Denial of Service (DoS)
Distributed Denial of Service (DDoS)
SQL Injection
Botnet
The dataset has been preprocessed, and techniques like Synthetic Minority Oversampling Technique (SMOTE) were applied to address class imbalances.

Algorithms and Techniques
The following algorithms and techniques were implemented and evaluated:

Gaussian Naive Bayes: A probabilistic model for baseline classification.
Decision Tree: A simple and interpretable tree-based model.
Random Forest: An ensemble method providing robustness and high accuracy.
XGBoost: A gradient boosting framework optimized for performance.
Max Voting Ensemble Technique: Combines predictions from multiple models for improved results.
