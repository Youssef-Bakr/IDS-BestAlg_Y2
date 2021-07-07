# IDS-BestAlg
Build IDS based on 7 different algorithms and compare thme to reach the best of them.

Abstract
An intrusion detection system (IDS) is a device or software application that monitors a
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

**imbalanced-learn**  are used as a fixer for unbalanced problem between normal(benign) and attack(bad) on our data.Our approach was tested on a
benchmark data set, KDD99, and the experimental outcomes show that models based
on Random Forest achieve the best accuracy for training and testing in both side (accuracy, and time consuming)

Looking at visualize of training accuracy

![training_accuracy_figure](https://user-images.githubusercontent.com/40705538/124690661-d30ccb80-deda-11eb-9e66-25944ed94e21.png)

Looking at visualize of testing accuracy

![testing_accuracy_figure](https://user-images.githubusercontent.com/40705538/124690732-e750c880-deda-11eb-8be0-84417283b770.png)

Looking at visualize of training time

![training_time_figure](https://user-images.githubusercontent.com/40705538/124690747-eddf4000-deda-11eb-894e-d0ba330a5f4c.png)


Looking at visualize of testing time

![testing_time_figure](https://user-images.githubusercontent.com/40705538/124690768-f3d52100-deda-11eb-9723-548e798f0202.png)
