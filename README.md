# ACML_Project

## COMS 4030A : Adaptive Computation and Machine Learning
### Dataset: Sign Language MNIST : Kaggle
### Task: 24-class static ASL hand gesture classification from 28×28 grayscale images

This notebook presents a complete end-to-end machine learning pipeline for recognising American Sign Language (ASL) hand gestures from still images. The dataset contains 27,455 training and 7,172 test images, each a 28×28 grayscale photograph of a hand forming one of 24 ASL letters (J and Z are excluded as they require motion).

### The notebook is organised as follows:

1. Data Loading & Exploration : understanding the dataset structure and class distribution
2. Preprocessing : normalisation, reshaping, encoding, and data splitting
3. Dimensionality Analysis (PCA) : motivating deep learning over flat classifiers
4. Baseline Models : Logistic Regression, SVM, Random Forest, MLP
5. Deep Learning — Architecture Comparison : SimpleCNN, DeepCNN, ResNetSmall, CNN+LSTM
6. Deep Learning — Keras-style CNN & 3-Layer CNN (PyTorch re-implementations)
7. Data Leakage Investigation : rigorous audit of the 100% accuracy anomaly
8. Regularised CNN — Honest Generalisation Estimate
9. Final Results & Model Comparison
10. Summary & Conclusions
