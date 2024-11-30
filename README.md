# ORADS-One class rule-based method to detecting unknown attacks using SRI in autonomous vehicles
A new rule-based approach to detect unknown attacks in Autonomous vehicles:

We have designed one class classifier to detect anomaly in CarChallenge2020 dataset and Car Hacking 2018 datset. To use the classifier, new features must be added to the test data (feature extraction) as given in the paper. These new features are: P_CAN_ID (previous CAN ID), PP_CAN_ID (previous of previous CAN ID), TimeInterval and TimePeriod. After finally preprocessed the test data, the classifier can be used directly to detect anomalies.
To show the imprtance of extracted features we have calculated correlation of each features with the class label for different attack types of Car hack 2018 dataset. Details are given in Correlation Calculation.pdf
