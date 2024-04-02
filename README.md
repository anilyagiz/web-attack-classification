#Web-Based Attack Detection using CSE-CIC-IDS2018 Dataset
#Introduction
#This project aims to detect web-based attacks using machine learning techniques applied to the CSE-CIC-IDS2018 dataset. The CSE-CIC-IDS2018 dataset is a publicly available dataset that contains various types of cyber attacks in a network environment. By training machine learning models on this dataset, we were able to achieve 100% accuracy in detecting web-based attacks.

#Dataset
The CSE-CIC-IDS2018 dataset is a comprehensive dataset that includes various features related to network traffic, such as flow duration, protocol type, service, source and destination IP addresses, and more. It contains both benign and malicious traffic samples, making it suitable for training and evaluating machine learning models for intrusion detection.

#Approach
We used a supervised learning approach to train our machine learning models. The dataset was preprocessed to handle missing values, normalize features, and encode categorical variables. We then split the data into training and testing sets, using a stratified split to ensure a balanced distribution of classes.

We experimented with several machine learning algorithms, including Random Forest, Support Vector Machines (SVM), and Gradient Boosting classifiers. Hyperparameter tuning was performed using techniques such as grid search and cross-validation to optimize the models' performance.

#Results
After training and evaluating our models, we achieved 100% accuracy in detecting web-based attacks on the testing set.
