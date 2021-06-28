# BINARY CLASSIFICATION MODEL

A Deep Neural Network Project


## Background

This is a sample project for Alphabet Soup, a venture capital firm. The business' team receives many funding applications from startups every day and  has asked for help to create a model that predicts whether applicants will be successful if funded by Alphabet Soup.

The business team has given  a CSV file containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. The CSV file contains a variety of information about each business, including whether or not it ultimately became successful. 

With my knowledge of machine learning and neural networks, I used the features in the provided dataset to create a binary classifier model that will predict whether an applicant will become a successful business.

---

## Technical Deliverables:

* Preprocess data for a neural network model.

* Use the model-fit-predict pattern to compile and evaluate a binary classification model.

* Optimize the model.


---

## Technologies

This project is written in Python with the following packages:

* TensorFlow
* Keras
* Sklearn
* Pandas

---

## Installation Guide

Before running the application first install and verify the following dependencies:

* Pandas from PyPI
```python
pip install pandas
```
* Tensor Flow from PyPI
```python
pip install --upgrade tensorflow
```
Verify Installation: 
```python
python -c "import tensorflow as tf;print(tf.__version__)"
```
The output of this command should show version 2.0.0 or higher.

* Keras, is a popular deep learning framework that serves as a high-level API for TensorFlow. Keras is now included with TensorFlow 2.0. So, run the following command to verify that the package is available:
```python
python -c "import tensorflow as tf;print(tf.keras.__version__)"
```
The output should show version 2.2.4-tf or later.


Next, Import the Modules

```python
# Imports
import pandas as pd
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder

import warnings
warnings.filterwarnings('ignore')
```

Clone to your repo and run

---


## Contributors

[Van Miller Sarcov Maquilan](https://www.linkedin.com/in/van-miller-sarcov-maquilan-20b472202/) 

---

## License

Feel free to add to this code, and use for your own project. :)
