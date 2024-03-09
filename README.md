# Chess Pieces Recognition using Deep Learning

## Project Overview

Chess Pieces Recognition is a deep learning project focused on classifying chess pieces from images using the powerful InceptionResNetV2 architecture. This project incorporates transfer learning techniques, leveraging pre-trained weights on ImageNet for feature extraction. The model is trained on a diverse dataset of chess pieces, and its performance is evaluated using various metrics, including accuracy, loss, confusion matrix, and a detailed classification report.

## Key Features

- **Transfer Learning with InceptionResNetV2:**
  - Utilizes the InceptionResNetV2 architecture for effective transfer learning and feature extraction.

- **Data Augmentation:**
  - Implements data augmentation techniques such as rotation, zooming, shifting, and flipping to enhance model generalization.

- **Visualization and Analysis:**
  - Generates visualizations for training and validation metrics, aiding in the analysis of model performance over epochs.

- **Early Stopping:**
  - Implements early stopping to prevent overfitting during model training.

- **Comprehensive Evaluation:**
  - Evaluates the model using metrics like accuracy, loss, confusion matrix, and a detailed classification report.

## Tech Stack

- **Deep Learning Framework:**
  - TensorFlow and Keras are employed for developing the deep learning model.

- **Transfer Learning Backbone:**
  - InceptionResNetV2 is used as the backbone architecture for transfer learning.

- **Data Preprocessing:**
  - ImageDataGenerator is applied for data preprocessing and augmentation.

## Usage

To replicate and run the project on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone (https://github.com/rakesh-vajrapu/chess-pieces-recognition).git
2. Install dependencies:
   pip install -r requirements.txt
3. Run the project:
   python chess_pieces_recognition.py
