# CIFAR-10 Image Classification

This project implements and compares multiple deep learning models on the CIFAR-10 dataset using TensorFlow and Keras.

## Models Implemented
- Artificial Neural Network (ANN)
- Convolutional Neural Network (CNN)
- CNN with Data Augmentation
- Improved CNN (32→64→128 filters)

## Training Strategies
- Data Normalization
- Dropout
- Batch Normalization
- Data Augmentation
- EarlyStopping

## Results

| Model | Accuracy |
|---------|---------|
| ANN | 43.57% |
| CNN | 64.53% |
| CNN + Augmentation | 65.12% |
| Improved CNN | 71.20% |

## Conclusion

The Improved CNN achieved the best performance with 71.20% accuracy. The results demonstrate that deeper convolutional architectures and training strategies such as augmentation and EarlyStopping significantly improve image classification performance on CIFAR-10.
