# Hybrid_CNN_CBR_Model
Hybrid CNN-CBR model for image classification
# Hybrid CNN-CBR Model for Image Classification

This repository contains an implementation of a hybrid deep learning and case-based reasoning (CBR) model to classify images. The project integrates a convolutional neural network (CNN) for feature extraction and a K-Nearest Neighbors (KNN)-based CBR for classification. 

## Project Overview

1. **Data Preprocessing**:
   - Images are preprocessed and resized to 150x150 pixels.
   - Data is divided into training and testing datasets.

2. **CNN Model**:
   - A convolutional neural network (CNN) is used for feature extraction.
   - Architecture:
     - Three convolutional layers.
     - Max-pooling layers.
     - Fully connected layers with dropout.

3. **CBR Integration**:
   - KNN is used for case-based reasoning (CBR).
   - Hybrid model combines CNN for feature extraction and KNN for classification.

4. **Evaluation**:
   - Confusion matrix, accuracy scores, and training curves are generated.

## Files Included

- `main.py`: Main code to execute the project.
- `requirements.txt`: List of Python libraries required for this project.
- `README.md`: Project description.

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/123456789dah/Hybrid_CNN_CBR.git
