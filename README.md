# Vegetable Classification Using CNNs

This project performs image classification on **15 types of vegetables** using three different Convolutional Neural Network (CNN) architectures — **VGG16**, **MobileNetV2**, and **ResNet50**. The entire pipeline, including data loading, model training, evaluation, and visualization, is implemented in a single Kaggle notebook.

---

## Notebook

The full project is implemented in a Kaggle notebook:

🔗 [Three CNN Architectures to Classify Vegetables](https://www.kaggle.com/code/andreamann/three-cnn-architectures-to-classify-vegetables)

---

## Dataset

The dataset is publicly available on Kaggle:

🔗 [Vegetable Image Dataset by misrakahmed](https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset)

### Dataset Summary

- **Total images**: 21,000  
- **Number of classes**: 15  
- **Image size**: 224 × 224  
- **Format**: `.jpg`  
- **Images per class**: 1,400  
- Data split: 70% training, 15% validation, 15% testing

### Classes

> Bean, Bitter Gourd, Bottle Gourd, Brinjal, Broccoli, Cabbage, Capsicum, Carrot, Cauliflower, Cucumber, Papaya, Potato, Pumpkin, Radish, Tomato

---

## Models Used

Three popular CNN architectures were used via transfer learning:

- **VGG16**
- **MobileNetV2**
- **ResNet50**

All models were fine-tuned on the same dataset using a consistent training pipeline to compare performance.

---

## Evaluation & Visualization

Each model was evaluated using:

- Classification report  
- Confusion matrix  
- Accuracy and loss plots  
- Prediction visualization

---

## Libraries & Tools

- TensorFlow / Keras  
- Scikit-learn  
- NumPy, Pandas  
- Matplotlib, Seaborn  

---
