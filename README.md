# codingTasks
Coding tasks

The name of the task is mnist_task.ipynb for image processing. This task asks the user to create a classification model, tune it and evaluate how well the model performs for image processing. This is important as it helps us to transform and manipulate thousands of images simultaneously, extracting valuable information from them, it also has many real world applications such as robotics, autonomous vehicles, and object detection. 

In this task, we must first load the MNIST dataset. Then we split the data into train and test sets. We then use the randomforestclassfier to create a classification model. Then we pick a parameter and tune it. We then print the confusion matrix and evaluate it. Lastly, we report on the accuracy, precision, recall and F1-score.

Installation

import numpy as np - pip install numpyimport pandas as pd

import matplotlib.pyplot as plt - python -m pip install -U pip 
                                  python -m pip install -U matplotlib

To install these use pip install scikit-learn

from sklearn.metrics import ConfusionMatrixDisplay 

from sklearn.metrics import accuracy_score, precision_score, recall_score, f1_score 

from sklearn.metrics import confusion_matrix 

from sklearn.ensemble import RandomForestClassifier 

from sklearn.model_selection import train_test_split

from sklearn.model_selection import GridSearchCV 

from sklearn.datasets import load_digits

Usage 

First import the libraries
<img width="1165" alt="Screenshot 2024-06-30 at 14 19 18" src="https://github.com/Ahmed01999/codingTasks/assets/129473521/0487af7f-1104-452d-b0a0-b0920fe2d4b7">

Assign the dataset to x and y, split into train and test sets and print the shape
<img width="1165" alt="Screenshot 2024-06-30 at 14 19 18" src="https://github.com/Ahmed01999/codingTasks/assets/129473521/eeb1bd36-ebf8-4fe7-90ed-179a90e82c49">

Create a classification model, pick a parameter and tune it and select a value to use for the testing on the test data
<img width="1369" alt="Screenshot 2024-06-30 at 14 27 30" src="https://github.com/Ahmed01999/codingTasks/assets/129473521/8d97ef13-d849-429f-ad4b-dc78d40802c6">

<img width="803" alt="Screenshot 2024-06-30 at 14 28 24" src="https://github.com/Ahmed01999/codingTasks/assets/129473521/8d62859e-24d0-4bcb-82ce-be4aaa3affa7">

Prints confusion matrix
<img width="1165" alt="Screenshot 2024-06-30 at 14 19 18" src="https://github.com/Ahmed01999/codingTasks/assets/129473521/e8cfb6e0-1bf8-4519-9ce1-e99c34f24169">

Evaluation of model
<img width="847" alt="Screenshot 2024-06-30 at 14 22 25" src="https://github.com/Ahmed01999/codingTasks/assets/129473521/cabdef8d-70ab-46df-b789-07753769263c">

