# IDS-BestAlg_Y2
Build an Intrusion Detection System (IDS) based on seven different algorithms and compare them to find the best one.
As an activity in the (Secure Intelligence) (Course by Ericsson)
Machine Learning security and different attacks and security models in machine learning with hands-on practice and real-world applications.

### Abstract
An Intrusion Detection System (IDS) is a device or software application that monitors a network for malicious activity or policy violations. It scans a network or system for harmful activity or security breaches. IDS can be network-based (NIDS) or host-based (HIDS), and they work by looking for signatures of known attacks or deviations from normal activity. In this project, we implemented machine learning and deep learning solutions for detecting attacks using the following seven algorithms:

- Gaussian Naive Bayes
- Decision Tree
- Random Rorest
- Support Vector Machine 
- Logistic Regression
- Gradient Boosting
- Artificial Neural Network

We addressed the problem of data imbalance between normal (benign) and attack (malicious) instances using the imbalanced-learn(https://imbalanced-learn.org/stable/index.html) library.

Our approach was tested on the KDD99 benchmark dataset, which can be found [here](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html). The experimental results demonstrate that models based on Random Forest achieve the best accuracy for training and testing, considering both accuracy and time consumption.

### Looking at visualize of training accuracy

![training_accuracy_figure](https://user-images.githubusercontent.com/40705538/124691786-b83b5680-dedc-11eb-8872-21a5b20af866.png)

### Looking at visualize of testing accuracy

![testing_accuracy_figure](https://user-images.githubusercontent.com/40705538/124691804-c1c4be80-dedc-11eb-9257-317cd4dbf028.png)

### Looking at visualize of training time

![training_time_figure](https://user-images.githubusercontent.com/40705538/124691822-c7ba9f80-dedc-11eb-8c12-42c655b49bd0.png)

### Looking at visualize of testing time

![testing_time_figure](https://user-images.githubusercontent.com/40705538/124691837-cf7a4400-dedc-11eb-9dcc-258afbcdf9ce.png)
