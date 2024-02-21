## Network Intrusion Detection System
A Network Intrusion Detection System (NIDS) is a security mechanism designed to monitor and analyze network traffic for signs of malicious activities or unauthorized access. Its primary purpose is to identify and respond to potential security threats in real-time.

### *Overview

This project focuses on building a Network Intrusion Detection System (NIDS) using four different datasets: `CICIDS 2017`, `CICIDS 2018`, `NSL KDD`, and `AWID`. Various machine learning models and deep learning techniques, including Logistic Regression, Extreme Gradient Boosting, CatBoost, Support Vector Machine, Decision Tree, RandomForest, and Long Short-Term Memory (LSTM), were employed for intrusion detection.

![Network](https://media.springernature.com/m685/springer-static/image/art%3A10.1007%2Fs44196-021-00047-4/MediaObjects/44196_2021_47_Fig3_HTML.png) 


### Datasets

The datasets used in this project are:

`CICIDS 2017:` [CICIDS-2017](https://www.kaggle.com/datasets/cicdataset/cicids2017/data)

`CICIDS 2018:` [CICIDS-2018](https://www.kaggle.com/datasets/cbskcjbsocb/cicids2018-clean-data)

`NSL KDD:` The data is available at this repository.

`AWID:` [AWID](https://icsdweb.aegean.gr/awid/)


### Models used on datasets and it's result

### `CICIDS 2017`

|ML Models|Accuracy|
|---|---|
|Logistic Regression|98.3 %|
|Decision Tree| 99.7 %|
|Random Forest()|99.7 %|

|DL Model|Accuracy|
|---|---|
|Long-Term Short Memory (LSTM)|98.8 %|

### `CICIDS 2018`

|ML Models|Accuracy|
|---|---|
|Logistic Regression|95.5 %|
|Decision Tree| 92.3 %|
|Random Forest|95.2 %|
|Extreme- Gradient Boost|94.76 %|
|Cat Boost|95.8 %|
|Support Vector Machine|95.5 %|

|DL Model|Accuracy|
|---|---|
|Long-Term Short Memory (LSTM)|99.5 %|

### `NSL KDD`

|ML Models|Accuracy|
|---|---|
|Logistic Regression|86.3 %|
|Decision Tree| 97.2 %|
|Random Forest|97.3 %|
|Support Vector Classifier|89.5 %|

|DL Model|Accuracy|
|---|---|
|Long-Term Short Memory (LSTM)|98.7 %|

### `AWID`

|ML Models|Accuracy|
|---|---|
|Logistic Regression|59.3 %|
|Decision Tree|88.1 %|
|Random Forest|93.03 %|

|DL Model|Accuracy|
|---|---|
|Long-Term Short Memory (LSTM)|99.6 %|

### `Note`: This project is a final year group project conducted by three team members i.e Aryan Kapri (Me), Binayak Koirala, and Ishika Adhikari. Ongoing research is being conducted, and a research paper based on this project is in progress.






