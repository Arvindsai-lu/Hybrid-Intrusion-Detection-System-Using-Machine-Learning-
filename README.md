## 📚 Project: Hybrid Intrusion Detection System (IDS)

### About the Project
- 🔒 This repository contains the implementation of a **Hybrid Intrusion Detection System** using machine learning techniques.
- 🕵️‍♂️ **Objective**: Detect and classify various network intrusion scenarios with high accuracy.
- 📊 **Dataset**: Uses the **CIC-IDS-2018 dataset**, covering diverse attack scenarios like DoS, DDoS, SQL Injection, and Botnet.

### Features
- 🚀 **Algorithms**:
  - Random Forest 🌳
  - XGBoost ⚡
  - Decision Tree 🌴
  - Gaussian Naive Bayes 📈
  - Max Voting Ensemble 🗳️
- 📈 **Techniques**:
  - Synthetic Minority Oversampling Technique (**SMOTE**) to handle imbalanced data.
  - Binary and Multi-class classification tasks with enhanced detection accuracy.

### 📊 Results Overview
| **Model**                 | **Accuracy (%)** | **F1-Score (%)** | **False Positive Rate (FPR)** |
|---------------------------|------------------|------------------|--------------------------------|
| Gaussian Naive Bayes      | 85.32           | 84.90           | 3.5%                          |
| Decision Tree             | 39.94           | 40.00           | 15.0%                         |
| XGBoost                   | 99.87           | 99.85           | 0.8%                          |
| Random Forest             | 100.00          | 99.90           | 1.9%                          |
| Max Voting Ensemble       | 95.08           | 94.80           | 2.1%                          |

### Installation and Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Arvindsai-lu/Hybrid-Intrusion-Detection-System-Using-Machine-Learning-.git
   cd Hybrid-Intrusion-Detection-System-Using-Machine-Learning
2. Install the Required Libraries
   command : pip install -r requirements.txt
   Run the scripts: Intrusion-Detection-System.ipynb

   if you have doubts read the file : How to run the script - IDS
