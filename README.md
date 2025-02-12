# 🐱 CatNet - Cat Image Classifier

CatNet is a simple machine learning project that classifies images as either a cat or not a cat using logistic regression. The dataset consists of labeled images of cats and non-cats, preprocessed and used to train a binary classification model.

## 📌 Features

- Loads and preprocesses the dataset (resizing, normalizing, and flattening images)

- Implements Logistic Regression from scratch

- Includes training, optimization, and prediction functions

- Provides test evaluations on new images

## 📂 Dataset Information

- 209 training images (64x64 RGB images)

- 50 test images (64x64 RGB images)

- Labels: 1 for cat, 0 for non-cat

## 💻 Tech Stack

- Python: Primary programming language
- NumPy: For numerical computations
- Matplotlib: For data visualization
- PIL (Pillow): For image handling
- SciPy: For scientific computing
- h5py: For handling dataset storage in HDF5 format

## 📊 Model Performance

- Achieves high accuracy in detecting cats using a basic logistic regression approach.

- You can improve the model by implementing deep learning using neural networks (e.g., TensorFlow/Keras).

## 🎯 Future Enhancements

- Implementing deep learning with a convolutional neural network (CNN)

- Expanding dataset for better generalization

- Integrating deployment via Flask or FastAPI
