# Network Intrusion Detection System using Machine Learning 🛡️
### Intrduction
🌐 In today's interconnected world, cybersecurity threats pose significant challenges to individuals and organizations alike. A crucial aspect of defending against these threats is the ability to detect and respond to network intrusions effectively. A Network Intrusion Detection System (NIDS) plays a vital role in this regard by monitoring network traffic for suspicious activity and alerting administrators to potential security breaches.

🛡️ In this project, we focus on building a NIDS using the nSL KDD dataset, a widely used benchmark dataset in the field of intrusion detection research. The dataset comprises a vast amount of network traffic data captured from various network activities, including both normal and malicious behavior. With around 1.5 lakh instances and 23 labels representing different types of network attacks, the NSL KDD dataset presents a challenging yet realistic scenario for developing intrusion detection systems.

### Preprocessing 🛠️
- Label encoding and one-hot encoding for categorical data conversion.
- Recursive Feature Elimination (RFE) for feature selection with Random Forest Classifier.

### Implemented Classifiers 🤖
1. Random Forest
2. K-Nearest Neighbors (KNN)
3. Support Vector Machine (SVM)
4. Principal Component Analysis (PCA)
5. Ensemble Voting Classifier
6. Gaussian Naive Bayes (NB)
7. XGBoost

### Implementation Details 📝
I have implemented each classifier using Python and relevant libraries such as scikit-learn, XGBoost, Matplotlib etc. The code is available in a Google Colab notebook due to the requirement of executing XGBoost, which cannot be done directly on a local system.

### Contact 📬
For any inquiries or feedback, please contact [Harsha G](mailto:harshag3106@gmail.com)

### Contributions 🤝
Contributions to this project are welcome! You can contribute by:
- Improving the efficiency of implemented classifiers.
- Enhancing the preprocessing techniques.
- Optimizing the feature selection process.
- Providing insights and suggestions for further improvements.
