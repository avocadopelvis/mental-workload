# Diagnosis of mental workload from ECG signals. (Research Project - IIT Kharagpur)

Mental workload reflects the amount of mental resources required to perform a set of concurrent tasks. Sustained high mental workload will cause mental fatigue, decreased performance, and even detrimental health effects in the long run.

ECG (Electrocardiogram) is a recording of the heart's electrical activity. ECG is a physiological signal that can quantitatively reflect the effect of mental workload on the human body. Differences in heart rate are observed with an increase in mental workload. Heart rate will increase as a task gets more difficult or if additional tasks are added

This project is an effort to use Deep Learning to understand the mental workload generated on an individual while performing a certain task and classify the task being performed.

# Goal
Given a ECG signal, classifiy the correct n-back task being performed.

# Tasks
* Performed data preprocessing using pandas to to convert the filtered signal data into samples of 15 seconds each.
* Implemented a Fully Connected Neural Network using PyTorch.
* Performed hyperparameter tuning to improve the accuracy on the validation data.
* Performed Data Augmentation to increase the training data by adding noise to the dataset.
* Worked on implementation of 1D CNN using PyTorch.
