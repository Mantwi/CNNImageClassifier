# CNNImageClassifier
This project involves the development of a convolutional neural network (CNN) to classify images from the Imagenette dataset. Utilizing PyTorch, this CNN is designed to demonstrate the essential elements of image classification including data preparation, model construction, training, and evaluation.

Project Overview

The classifier tackles the challenge of distinguishing between different categories of images using the Imagenette dataset, a subset of ImageNet that includes 10 easily recognizable classes. This project provides insights into handling image data, implementing convolutional layers, and optimizing neural networks.

Features
-Model Architecture: The CNN consists of sequential convolutional layers paired with ReLU activations and max pooling to extract features, followed by a series of fully connected layers to perform classification.
- Data Management: Integration with Google Colab and PyTorch's DataLoader for efficient management of data splits into training, validation, and test sets.
- Optimization and Training: Uses the Adam optimizer with a dynamic learning rate and cross-entropy loss function to find the optimal model weights.
- Performance Evaluation: Implements a training loop with detailed logging of training and validation metrics to monitor overfitting and underfitting dynamically. The model with the best validation performance is saved and evaluated on the test set to ensure generalizability.

 Technologies Used

- PyTorch: For building and training the neural network model.
- NumPy: For high-performance numerical computation.
- Matplotlib: For plotting training and validation loss and accuracy graphs to visualize the model's performance.
- Google Colab: Provides a robust, zero-configuration cloud-based runtime with GPU support.
