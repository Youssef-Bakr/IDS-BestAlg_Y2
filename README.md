# IDS-BestAlg
Build IDS based on 7 different algorithms and compare thme to reach the best of them.

### Abstract
An intrusion detection system ([IDS](https://en.wikipedia.org/wiki/Intrusion_detection_system)) is a device or software application that monitors a
network for malicious activity or policy violations. It scans a network or a system for a
harmful activity or security breaching. IDS protects networks (Network-based intrusion
detection system NIDS) or hosts (Host-based intrusion detection system HIDS),
and work by either looking for signatures of known attacks or deviations from normal
activity. **Machine learning** and **Deep learning** algorithms proved their effectiveness in intrusion detection In this project, we implemented machine/deep
learning solutions for detecting attacks based on seven different algorithms
- Gaussian Naive Bayes
- Decision Tree
- Random Rorest
- Support Vector Machine 
- Logistic Regression
- Gradient Boosting
- Artificial Neural Network

[**imbalanced-learn**](https://imbalanced-learn.org/stable/index.html)  are used as a fixer for unbalanced problem between normal(benign) and attack(bad) on our data.

Our approach was tested on a benchmark data set, [**KDD99**](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html), and the experimental outcomes show that models based
on [**Random Forest**](https://en.wikipedia.org/wiki/Random_forest) achieve the best accuracy for training and testing in both side (accuracy, and time consuming)

Looking at visualize of training accuracy

![training_accuracy_figure](https://user-images.githubusercontent.com/40705538/124691786-b83b5680-dedc-11eb-8872-21a5b20af866.png)

Looking at visualize of testing accuracy

![testing_accuracy_figure](https://user-images.githubusercontent.com/40705538/124691804-c1c4be80-dedc-11eb-9257-317cd4dbf028.png)

Looking at visualize of training time

![training_time_figure](https://user-images.githubusercontent.com/40705538/124691822-c7ba9f80-dedc-11eb-8c12-42c655b49bd0.png)

Looking at visualize of testing time

![testing_time_figure](https://user-images.githubusercontent.com/40705538/124691837-cf7a4400-dedc-11eb-9dcc-258afbcdf9ce.png)
