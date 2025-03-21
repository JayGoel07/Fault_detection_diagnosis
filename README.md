Fault Diagnosis of Three-Phase Currents using Machine Learning
This repository contains implementations of Hierarchical Risk Classifier (HRC) using CNN, SVM, and Naïve Bayes for fault diagnosis in three-phase current systems. The dataset used for training and evaluation was generated using MATLAB, and the results are summarized in results.png.

Project Overview
Electrical faults in three-phase current systems can lead to severe operational issues. This project leverages machine learning techniques to classify and diagnose faults efficiently.

Files in This Repository
hrc_cnn.ipynb – Implements fault diagnosis using a Convolutional Neural Network (CNN).
hrc_svm.ipynb – Implements fault classification using Support Vector Machine (SVM).
hrc_nb.ipynb – Uses Naïve Bayes (NB) for fault detection.
results.png – Visualization of the model performance and classification results.
Dataset
The dataset consists of fault diagnosis data for three-phase currents, generated in MATLAB.
The data includes normal and faulty conditions for different electrical fault types.
Results
The performance of the implemented models is documented in results.png.
Comparative analysis of CNN, SVM, and NB models is provided.
Usage
Clone this repository:
bash
Copy
Edit
git clone https://github.com/JayGoel07/fault-diagnosis-3phase
cd fault-diagnosis-3phase
Open the Jupyter notebooks and run the models on the dataset.
License
This project is open-source and available for research and educational purposes.
