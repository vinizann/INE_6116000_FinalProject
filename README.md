This repository holds neural networks implementation for traffic sign classification.
It is the final project developed in INE6116000 - Inteligência Artificial Conexionista discipline from my PhD course at UFSC.

The dataset is available at: https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign
It has the following properties:
- Single-image, multi-class classification problem
- More than 40 classes
- More than 50000 images in total

The following experiments were performed:
- Convolutional Neural Network (CNN)
- Multi-layer Perceptron (MLP)
- Logistic Regression (LR)

The best results were obtained by using CNN model, which was expected since it is the state of the art for image classification.
The CNN model achieved 99.8% of accuracy for training data and 97.6% for test data.