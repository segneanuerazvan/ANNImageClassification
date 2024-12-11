# Artificial Neural Networks for Multi-Class Image Classification

This project focuses on building and implementing an **Artificial Neural Network (ANN)** for classifying images into multiple categories. By leveraging Python, TensorFlow, and Keras, the model is designed to handle complex datasets and achieve high accuracy through data preprocessing, augmentation, and optimization techniques.

The aim of this project is to explore and demonstrate the application of ANNs in real-world image classification tasks.

## Key Features
- Preprocessing and augmentation of image data to improve model generalization.
- Custom ANN architecture designed for multi-class classification problems.
- Visualization of model performance metrics, including accuracy and loss graphs.
- Integration with publicly available datasets for easy reproducibility.

## Technologies Used
- **Python**: Core programming language for implementation.
- **TensorFlow & Keras**: Framework and API for designing and training neural networks.
- **NumPy**: Efficient data manipulation.
- **Matplotlib**: Visualizing training and testing results.

## Dataset Overview
The dataset used contains labeled images for multi-class classification tasks. It is publicly available on Kaggle and can be downloaded using the following steps:
1. Access the dataset here: [Animals Dataset on Kaggle](https://www.kaggle.com/datasets/alessiocorrado99/animals10).
2. Download and extract the dataset into the `data/` folder of this repository.
3. Alternatively, use the Kaggle API to download the dataset directly:
   ```bash
   pip install kaggle
   kaggle datasets download -d alessiocorrado99/animals10
   unzip animals10.zip -d data/
