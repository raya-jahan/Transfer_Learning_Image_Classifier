Transfer Learning for CIFAR-10 Image Classification:

This project implements a deep learning model for image classification using Transfer Learning with a pre-trained VGG19 network model on the CIFAR-10 dataset. The model leverages fine-tuning techniques to enhance performance, using custom training and evaluation loops for accuracy tracking and loss computation.

Key Features:

- Model Architecture: VGG19 with custom classifier layers
- Dataset: CIFAR-10 (10 image classes including cats, dogs, ships, and more)
- Training: Fine-tuning second-final output layers with CrossEntropyLoss and Adam optimizer
- Evaluation: Custom accuracy and epoch loss functions with visualization of predictions

Tech Stack & Libraries:

- Python
- PyTorch (`torch`, `torchvision`)
- NumPy, pandas, matplotlib
- Jupyter Notebook

How It Works:

1. Preprocessing: Images resized to 224x224, normalized using ImageNet standards.
2. Model Setup: Loaded pre-trained VGG19 and modified classifier layers for CIFAR-10 classes.
3. Training: Ran the model on GPU with custom loss and accuracy computations.
4. Evaluation: Tested on unseen data and visualized predictions alongside true classes.

Sample Output:

Training accurary: 84%, Testing accuracy: 82.4%
