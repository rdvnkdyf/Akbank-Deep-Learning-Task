# Akbank-Deep-Learning-Task
The required homework notebook for the Akbank Deep Learning Bootcamp.

Library Imports:

Imports essential libraries for deep learning (tensorflow), data processing (ImageDataGenerator), and plotting (matplotlib).
Dataset Path:

Defines the path to the fish dataset stored in the Kaggle environment.
Data Preprocessing:

Sets image dimensions (128x128) and batch size (32).
Uses ImageDataGenerator for image augmentation and splitting into training (80%) and validation (20%) sets.
Model Building:

Creates an ANN model with several dense layers, each followed by batch normalization and dropout (to prevent overfitting).
The final layer uses softmax for multi-class classification.
Model Compilation:

Uses Adam optimizer with a learning rate of 0.0001 and categorical cross-entropy for classification.
Training:

The model is trained for 30 epochs, with training and validation accuracies tracked.
Plotting:

Plots the accuracy of both training and validation over the epochs to visualize performance trends.

Kaggle Notebook Link:https://www.kaggle.com/code/rdvankadayifi/akbank-derin-renme-devi-notebook-u
