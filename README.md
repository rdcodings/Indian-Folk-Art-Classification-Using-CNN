# Indian Folk Art Classification Using Convolutional Neural Networks

## Overview

This project focuses on the classification of diverse Indian folk art forms using Convolutional Neural Networks (CNNs). By automating the classification process, we aim to facilitate the cataloging, retrieval, and analysis of folk art images, thus contributing to the preservation and promotion of cultural heritage.

## Dataset

The dataset comprises 32,310 high-resolution images organized into 30 classes, each representing a distinct form of Indian folk art. These images are labeled with their respective art forms and regions of origin, providing valuable cultural insights.

## Key Features

- **Diverse Art Forms**: Includes 30 types of Indian folk art, such as Warli, Madhubani, Pattachitra, and Kalamkari.
- **High Resolution**: Suitable for detailed analysis and artistic study.
- **Well-Organized**: Images are categorized into 30 classes with dedicated folders for each art form.
- **Cultural Insight**: Each image is labeled with the art form and its region of origin.

## Model Architecture

The CNN model is designed with:
- Three convolutional layers with increasing filter sizes (32, 64, 128) and ReLU activation.
- Max pooling layers to reduce spatial dimensions.
- A fully connected dense layer with 512 neurons.
- A softmax output layer with 30 neurons for multi-class classification.

## Training

- **Optimizer**: Adam
- **Loss Function**: Categorical Cross-Entropy
- **Metrics**: Accuracy

The model achieved a validation accuracy of 70.92% over 25 epochs.

## Evaluation

- **Confusion Matrix**: To visualize classification performance.
- **Classification Report**: Detailed metrics including precision, recall, and F1-score for each class.
- **ROC and Precision-Recall Curves**: Additional performance evaluation metrics.

## Usage

This dataset and model can be used for:
- Training and testing image recognition and classification models.
- Cultural and historical research on Indian folk art.
- Educational purposes to promote awareness of Indian cultural heritage.
- Artistic inspiration and design purposes.

## Acknowledgements

Special thanks to Isha Thakur for contributing to the dataset. This project aims to preserve and promote the rich cultural heritage of India through digital means.

## Author

Rajarshi Das
