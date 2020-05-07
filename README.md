# ids2018
The goal of this project was to use the CSE-CIC-IDS2018 dataset to begin building an anomaly-based network intrusion detection engine using deep learning techniques. The purpose of anomaly-based intrusion detection is to classify all system activity as either “anomalous” or “normal”, allowing for detection of unusual, potentially malicious traffic. Such anomaly-based intrusion detection systems could exist at either the network or the host level. This project focuses on classifying network traffic.

In order for this type of system to work, it is necessary for the engine to learn what “normal” and “anomalous” behavior look like. By utilizing existing labeled network data sets which contain examples of both normal and malicious traffic, this engine can be trained using any number of machine learning techniques, though this project focuses specifically on deep learning techniques.

An additional constraint of this project is that due to the size of the chosen dataset, only a portion of the data related to web-based attacks was used. Though only a piece of the dataset is included, this approach can be generalized easily to include the entire dataset.
