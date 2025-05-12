# Monitoring-and-Detecting-Cyber-Attacks-Based-on-Traffic-Data
SE495 Project - [Colab Code Notebook](https://colab.research.google.com/drive/19bYZxy2dF4q4zFShBgvPX9tqPwK37l0k?usp=sharing)

## 📄 Project Overview  
 
Cybersecurity threats are evolving at a very fast pace, becoming more complex and frequent. Threats such as botnets, DDoS attacks, and malicious traffic are becoming more sophisticated, thus posing greater risks to organizations and becoming more challenging for them to protect their systems. That’s why it's very important for organizations to be able to  accurately detect and classify various types of cyberattacks in real-time, to ensure network security is maintained. The project aims to leverage machine learning models to monitor and detect cyberattacks using network traffic data and DNS information. By analyzing features like traffic duration, packet size, and timestamps, the models can classify traffic as normal or malicious and identify specific attack types. 

## 🚀 **Impact**
- **Automating threat detection:** Less reliance on manual monitoring.
- **Improving accuracy:** Machine learning models outperform traditional signature-based methods.
- **Reduced Response Time:** Using automation threat detection, the time taken to detect the attack once the attack is initiated will be reduced, minimizing potential damage.

## 🎯 **Objective**

The main objective of this project is to build, train, and evaluate various machine learning models that are capable of accurately detecting and classifying cyberattacks based on network traffic data. Let’s explore some of the sub-objectives of this project.

- **Train Binary and Multi-Class Classifiers** 
- **Compare Model Performance** 
- **Identify Most Important Features** 
- **Dashboard Visualization**


## 🔧 **Methodology**

- **Data Collection**:
  - **Dataset Name:** combined_dataset (CSV format)
  - **Size:** 130,502 samples & 17 features
  - **Target Variable:** attack_type
 
- **Data Prepprocessing**:
  - **Handling Missing Values:** Median / Mode Imputation
  - **One-Hot Encoding:** Label encoding was used for any categorical data
  - **Feature Scaling:** Numeric features were standardized using StandardScaler
 
- **Models trained**:
  - **Logistic Regression** 
  - **Random Forest** 
  - **Gradient Boosting** 
  - **SVM**
  - **Neural network**
 

## 🔎 **Results**
- **Best Model:** Random Forest performed the best in both tasks (Perfect 1s)
- **Top 5 Most Important Features:** 1-Proto 2-StartTime 3-Dir 4-TotBytes 5-Dur
- **Deep Learning:** he deep learning model achieved comparable results to traditional machine learning approaches, with only slightly lower performance. This suggests that additional complexity may not be necessary for this particular dataset.
- **Class Imbalance:** The extreme imbalance in the dataset (99.9% botnet vs. 0.1% normal) is significant which risks overfitting. 


## ✅ **Conclusion**

In this project, I was able to develop and evaluate multiple machine learning and deep learning models for cyber attack detection based on network traffic data. All models performed exceptionally well which demonstrates the effectiveness of machine learning approaches for cybersecurity applications. The Random Forest classifier emerged as the optimal model, achieving perfect scores across all evaluation metrics for both binary and multi-class classification tasks. Key features like protocol, startt time, and direction of network traffic were critical. The dashboard enables real-time monitoring, aiding security teams in threat response.


