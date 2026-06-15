# ANN Churn Classification

## Project Overview

This project focuses on implementing an Artificial Neural Network (ANN) to predict customer churn using banking customer data. The objective is to identify customers who are likely to leave the bank based on demographic and financial attributes.

## What I Learned

* Data preprocessing and feature engineering
* Handling categorical variables using Label Encoding and One-Hot Encoding
* Feature scaling using StandardScaler
* Building and training Artificial Neural Networks (ANNs) with TensorFlow and Keras
* Understanding forward propagation, backpropagation, activation functions, and optimization
* Monitoring model training using TensorBoard
* Saving and loading trained models and preprocessing objects using Pickle
* Creating an interactive web application using Streamlit
* Version control and project management using Git and GitHub

## Technologies Used

* Python
* TensorFlow / Keras
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* TensorBoard
* Streamlit

## Project Workflow

1. Data preprocessing and cleaning
2. Encoding categorical features
3. Feature scaling
4. Train-test split
5. ANN model creation and training
6. Model evaluation
7. Model persistence using `.h5` and `.pkl` files
8. Streamlit application development
9. Model deployment and prediction

## Files Included

* `app.py` – Streamlit application
* `experiments.ipynb` – Model training notebook
* `prediction.ipynb` – Prediction and testing notebook
* `model.h5` – Trained ANN model
* `scaler.pkl` – Saved StandardScaler
* `label_encoder_gender.pkl` – Gender encoder
* `onehot_encoder_geo.pkl` – Geography encoder
* `requirements.txt` – Project dependencies

## Results

The ANN model was trained to classify whether a customer is likely to churn or remain with the bank. TensorBoard was used to visualize training metrics such as loss and accuracy throughout the training process.

## How to Run

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Author

Krish Agrawal
