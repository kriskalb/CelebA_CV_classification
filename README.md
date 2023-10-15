# CelebA Image Attractiveness Prediction Project

## Overview
The CelebA Image Attractiveness Prediction Project is a deep learning project that focuses on predicting image attractiveness using a dataset containing 50,000 images. We have developed a deep learning model based on Inception v3 architecture and integrated various image-related features from a CSV file into the modeling process. Additionally, we conducted a comprehensive comparison of evaluation metrics for the deep learning model.

## Project Goals
The primary goals of this project are:
1. To build a deep learning model capable of predicting the attractiveness of images.
2. To leverage a large dataset and advanced deep learning techniques to achieve accurate predictions.
3. To compare the performance of the deep learning model with other evaluation metrics.

## Main Features
- Deep Learning Model: We implemented a deep learning model based on the Inception v3 architecture (transfer learning) to predict image attractiveness.
- Data Integration: We integrated image-related features from a CSV file into the modeling process to enhance prediction accuracy.
- Evaluation Metrics Comparison: We conducted a thorough comparison of evaluation metrics to assess the model's performance.
- Classifivation Models: We implemented the following classification models to feature dataset:
   - Logistic Regression
   - Decision Trees Classifier
   - Random Forest Classifier
   - SVClassifier
   - Adaboost
## Technologies Used
The project was developed using the following technologies and tools:
- Python: We used Python as the primary programming language for data preprocessing, model development, and analysis.
- TensorFlow/Keras: TensorFlow was used to build and train the deep learning model. We used a ready-made Inception V3 model and adapted it to our imageset.
- Advanced Guide to Inception v3 - https://cloud.google.com/tpu/docs/inception-v3-advanced
- scikit-learn: scikit-learn library was employed for various data preprocessing tasks and metric comparisons.
- pandas: pandas library was used for data manipulation and feature integration.

## Installation Instructions
To run this project locally, follow these steps:

1. Clone the repository:
   git clone 'https://github.com/kriskalb/celeba-image-attractiveness-prediction'
2. Navigate to the project directory:
   cd celeba-image-attractiveness-prediction
3. Install the required Python packages:
   pip install -r requirements.txt
4. Follow the instructions in the Jupyter Notebook or Python script to preprocess data, build the model, and evaluate its performance.

## Authors
- kriskalb

## License
This project is open-source
