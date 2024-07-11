# PCOS-Detect
This project detects Polycystic Ovary Syndrome (PCOS) using a Support Vector Machine (SVM) classifier. The application allows users to upload images, which are then processed and classified to determine the likelihood of PCOS.

### Project Overview
This repository contains code and resources for a machine learning project aimed at detecting PCOS. The primary model used is an SVM classifier trained using GridSearchCV for hyperparameter tuning. Additionally, the project includes implementations of other classifiers such as Naive Bayes, Decision Tree, and Random Forest for comparison.

### Repository Contents
##### PCOS SVM.ipynb: Jupyter notebook containing the main code for training and testing the SVM model.
##### pcos.py: Streamlit app code for deploying the PCOS detection web application.
##### PCOS.jpg: Example image where the model predicts PCOS.
##### nonPCOS.jpg: Example image where the model predicts no PCOS.
##### pcos_demo.mp4: Demo video showcasing the web interface of the application.
### Model Training
The model training involves the following steps:

Data Preparation: Load and preprocess the images. Images are resized and flattened to be used as input for the model.
Model Selection: Different models (Naive Bayes, Decision Tree, Random Forest, and SVM) are trained and evaluated.
Hyperparameter Tuning: GridSearchCV is used to find the best parameters for the SVM model.
Model Evaluation: The models are evaluated using accuracy score and classification report.
