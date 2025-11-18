# Brain Tumor Classification using CNN

This project builds a deep learning model using Convolutional Neural Networks (CNNs) to classify MRI brain scans into **tumor vs. non-tumor** categories. It demonstrates skills in handling image datasets, preprocessing, augmentation, and building a high-accuracy Keras/TensorFlow model.

---

## Project Summary
Brain tumor diagnosis using MRI scans is critical for early detection and treatment. This project creates a classification model that learns image features and predicts whether a tumor is present.

The final model achieves strong accuracy and includes visualizations of training performance and prediction outputs.

---

## Features
- Image preprocessing (resizing, normalization)
- Data augmentation using `ImageDataGenerator`
- CNN built with TensorFlow/Keras
- Model evaluation (accuracy, confusion matrix)
- Predictions on new images
- Visualization of training/validation curves

---

## Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## Dataset
Public dataset containing MRI images of brain scans labeled as:
- **yes** → tumor present  
- **no** → tumor absent

---

## Future Improvements

* Deploy model as a web app (Streamlit)

* Add segmentation-based tumor localization

* Train using transfer learning (ResNet, EfficientNet)

