# VGG16-Multi-Class-Image-Classification
This project implements a deep learning pipeline to classify images of flowers into multiple categories using the pre-trained VGG16 model


Project Features
Data Preparation:

Organizes the flower dataset into train, test, and optional predict folders.
Uses data augmentation techniques (random flipping, zooming, shearing) to enhance model performance.
Model Architecture:

Adapts the VGG16 model by adding custom dense layers for flower classification.
Freezes pre-trained layers initially for training the added layers and fine-tunes select layers later for better accuracy.
Training and Fine-Tuning:

Trains the model for 10 epochs using categorical crossentropy as the loss function.
Fine-tunes the last few layers of the VGG16 model for domain-specific optimization.
Evaluation and Visualization:

Evaluates model performance on a validation set.
Visualizes training and validation accuracy/loss to track progress.
Prediction:

Classifies new, unlabeled flower images and maps predictions to their respective class names.
