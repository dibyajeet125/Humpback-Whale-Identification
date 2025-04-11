# Humpback-Whale-Identification
Developed a CNN model for humpback whale identification, achieving 94.74% training accuracy on a dataset of 25,361 images across 5,005 classes. This project leveraged data augmentation to enhance model performance and mitigate overfitting.



This project utilizes Convolutional Neural Networks (CNNs) to identify humpback whales based on unique tail patterns. The goal is to contribute to conservation efforts by accurately classifying whales from a large dataset.

Project Overview

Dataset: The dataset consists of 25,361 images, categorized into 5,005 distinct classes. This presents a challenging multi-class classification problem.

Data Preprocessing: Images are resized to 100x100 pixels and normalized by dividing pixel values by 255 to ensure consistent input for the neural network.

Model Architecture: A CNN model is designed with multiple convolutional layers, max-pooling, batch normalization, and dropout. The model is compiled with the Adam optimizer and categorical cross-entropy loss.

Data Augmentation: To combat overfitting and enhance dataset diversity, data augmentation techniques are applied, including rotation, zooming, and horizontal flipping.

Key Achievements

Training Performance: The model achieves a training accuracy of 94.74% and a training loss of 0.1746 after 50 epochs with a batch size of 64.

Learning Rate Scheduler: A learning rate reduction callback is implemented to adjust the learning rate based on performance metrics, ensuring optimal convergence.

DATASET LINK: https://www.kaggle.com/competitions/humpback-whale-identification/data?select=train.csv
