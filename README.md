# Nettrusion-detection

Network traffic anomaly detection (intrusion detection task)
------------

**Theory and Methods**
The data that we are going to use for this is a subset of an open source default of Intrusion detection evaluation dataset (ISCXIDS2012) from the the Canadian Institute for Cybersecurity repository: https://www.unb.ca/cic/datasets/ids.html. In order to download this dataset, you have to pass a short registration.

The intend for this dataset is to assist various researchers in acquiring datasets of this kind for testing, evaluation, and comparison purposes, through sharing the generated datasets and profiles. The full research paper outlining the details of the dataset and its underlying principles. Please include this citation if you plan to use this database:

Ali Shiravi, Hadi Shiravi, Mahbod Tavallaee, Ali A. Ghorbani, Toward developing a systematic approach to generate benchmark datasets for intrusion detection, Computers & Security, Volume 31, Issue 3, May 2012, Pages 357-374, ISSN 0167-4048, 10.1016/j.cose.2011.12.012.

During the work, you will know about the anomaly detection task which is the main machine learning task solved by different algorithms correlating to the identification of rare items, events or observations which raise suspicions by differing significantly from the majority of the data. In essence, anomaly detection can be used as a tool for many other tasks, such as intrusion detection, fraud detection, fault detection, system health monitoring, event detection in sensor networks, detecting ecosystem disturbances, and defect detection in images using machine vision, etc.

Moreover, you will be provided 12 files of data. You should select one among them. Training some of them by .fit method takes a lot of time, so you can select not all the data files. In addition, you should select some values of hyperparameters in this Lab, and the Lab execution duration will depend on your choice.

Anomaly detection has three broad categories based on anomaly detection techniques: unsupervised, supervised and semi-supervised anomaly detection.

In addition, we will build the visualization of our results, exactly the obtained metrics (accuracy and loss) to choose the best model for further saving and predicting based on this saved model.
