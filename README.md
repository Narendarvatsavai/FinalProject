
# Human Activity Recognition Using Machine Learning

This project implements machine learning models to predict human activities based on sensor data. Models such as Decision Tree, Random Forest, and Support Vector Machine (SVM) are trained and evaluated for accuracy and performance.

---

## Table of Contents

1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Data Preprocessing](#data-preprocessing)
6. [Machine Learning Models](#machine-learning-models)
7. [Evaluation Metrics](#evaluation-metrics)


---

## Overview

The goal of this project is to classify human activities using data from wearable sensors. The models are trained using the provided training dataset and evaluated on the test dataset.

---

## Dataset

The dataset contains the following:
- **Features**: Sensor readings from wearable devices.
- **Target Variable**: `Activity`, representing the type of human activity.

Activities include various physical movements recorded by the sensors.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/human-activity-recognition
   cd human-activity-recognition
   ```

2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Place the datasets (`train.csv` and `test.csv`) in the project directory.

---

## Usage

Run the script in jupyter notebook
```bash
final_code.ipynb
```

---

## Data Preprocessing

1. **Handling Missing Values**: Checked and handled missing values in the datasets.
2. **Label Encoding**: Encoded the `Activity` column into numerical format.
3. **Feature Scaling**: Standardized features using `StandardScaler`.


## Machine Learning Models

The following models are implemented and evaluated:
1. **Decision Tree**
2. **Random Forest**: 100 estimators with default parameters.
3. **Support Vector Machine (SVM)**: Linear kernel.

---

## Evaluation Metrics

The models are evaluated using:
- **Accuracy**: Overall correctness of predictions.
- **Classification Report**: Includes precision, recall, F1-score, and support for each activity class.
- **Confusion Matrix**: Displays true vs predicted classifications.

---

