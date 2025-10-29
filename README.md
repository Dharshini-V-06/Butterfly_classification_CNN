##  Butterfly Species Classification

###  Overview

This project classifies butterfly species using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.
It applies transfer learning with MobileNetV2 for efficient feature extraction and achieves around 79% validation accuracy across 75 classes.

---

###  Features

* Uses MobileNetV2 pretrained on ImageNet
* Classifies 75 butterfly species
* Includes image augmentation for better generalization
* Early stopping and checkpointing for optimal training
* Ready for Streamlit deployment

---

###  Dataset

* Contains training and testing images with labels
* 75 unique butterfly classes
* Training and testing details stored in CSV files (`Training_set.csv`, `Testing_set.csv`)
* Data split into 80% training and 20% validation

---

###  Model Details

* Base Model: MobileNetV2 (frozen layers for feature extraction)
* Custom top layers for 75-class classification
* Input image size: 128×128 pixels
* Optimizer: Adam
* Loss Function: Categorical Crossentropy
* Metrics: Accuracy

---

###  Results

* Validation Accuracy: **~79.1%**
* Training stabilized by early stopping
* Smooth accuracy and loss curves without overfitting

---

###  Saved Model

* Best model saved as `best_butterfly_model.keras`
* Used for inference and Streamlit deployment

---

###  Future Work

* Fine-tune MobileNetV2 for better accuracy
* Add Grad-CAM visualization
* Experiment with EfficientNet or Vision Transformers
* Expand dataset for rare species

---

---

Would you like me to make this even shorter (a 5-section summary suitable for GitHub repo top)?
