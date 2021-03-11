# seizure_detection

# Automatic detection of seizure activity from EEG time series data

In this mini-project, I attempt to apply different machine learning models to automatically classify EEG time series into diseased (seizure) and healthy (non-seizure) groups. To do this, i applied signal processing (Filtering, Fourier, and Wavelet transforms) to each EEG recording to obtain a feature space. Using SKlearn pipelines, I compared all the classical models including logistic regression, SVM, and KNNs with ensemble tree-based methods such as random-forest and XGboost.

I also apply a convolutional neural network model (Tensorflow/Keras) to classify overlapping 2 s windows of EEG time series. Although, deep-learning was not necessary in this problem, its use was just for didactic purposes.


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

## Authors

* **David Fox** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)
