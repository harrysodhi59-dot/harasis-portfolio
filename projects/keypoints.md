😊 Facial Keypoint Detection Using Transfer Learning (CNN Project)
📌 Overview

This project implements facial keypoint detection using a transfer learning–based Convolutional Neural Network (CNN).
The goal was to predict key facial landmarks such as:

Eyes

Nose tip

Mouth corners

Eyebrows

This type of model is used in applications such as face alignment, AR filters, driver monitoring, and medical symptom analysis.

🎯 Project Objectives

Stream data from an online dataset (Kaggle facial keypoints dataset)

Apply transfer learning to build an accurate CNN model

Train a network capable of predicting facial landmarks

Visualize predictions and evaluate training performance

This project demonstrates skills in deep learning, data pipelines, and applied transfer learning.

🧹 Data Preparation

Steps included:

Loading grayscale facial images (96×96 resolution)

Normalizing pixel values

Handling missing keypoint labels

Splitting into training/validation sets

Applying transformations for robustness

Resizing

Normalization

Image augmentation

🤖 Model Architecture

Using transfer learning, a pre-trained CNN was adapted to predict 30 keypoint values (x,y pairs).

Model features:

Convolutional feature extractor (from pre-trained weights)

Fully connected regression head

Optimizer: Adam

Loss: MSELoss

Metrics: Training/validation loss

This approach dramatically improved accuracy compared to training from scratch.

📈 Model Training & Evaluation

During training, we monitored:

Loss curves

Overfitting behaviour

Model stability

Prediction quality

🔍 Results included:

Smooth downward training/validation loss

Clear keypoint placement on test images

Model generalized well to unseen faces

Visual outputs included predicted points overlaid on sample images.

🖼️ Visual Examples

Predictions demonstrated:

Accurate eye and eyebrow detection

Correct placement of nose and mouth keypoints

Strong consistency across images

(You may add screenshots of your predicted outputs later.)

🔧 Tools & Libraries

Python

PyTorch

TorchVision

NumPy

Matplotlib

Kaggle API

👤 My Role

I completed:

Dataset preparation and loading

Transfer learning model setup

Training loop implementation

Evaluation and visualization

Documentation of results

🧩 Reflection

From this project, I learned:

How transfer learning speeds up deep learning model development

How to design CNN-based regression models

The importance of proper preprocessing and augmentation

How to visualize and interpret predicted keypoints

This project strengthened my deep learning skills and understanding of facial landmark detection.

📌 Next project: Customer Churn Prediction
