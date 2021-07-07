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
imbalanced-learn  are used as fixer for unbalanced on our data.Our approach was tested on a
benchmark data set, KDD99, and the experimental outcomes show that models based
on Random Forest achieve the best accuracy for training and testing in both side (accuracy, and time consuming)

Looking at training accuracy
![training_accuracy_figure](https://user-images.githubusercontent.com/40705538/124690448-81644100-deda-11eb-8500-f06065f5cbb5.png)

Looking at testing accuracy
![testing_accuracy_figure](https://user-images.githubusercontent.com/40705538/124689436-d2733580-ded8-11eb-91cc-e38ae9087e3a.png)

Looking at training time
![training_time_figure](https://user-images.githubusercontent.com/40705538/124689470-ddc66100-ded8-11eb-8731-353dac5d74f8.png)

Looking at testing time
![testing_time_figure](https://user-images.githubusercontent.com/40705538/124689486-e3bc4200-ded8-11eb-9d0a-ba78f3af57a7.png)
