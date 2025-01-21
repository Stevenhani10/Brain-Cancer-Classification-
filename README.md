# Brain-Cancer-Classification-
This project uses a Convolutional Neural Network (CNN) to classify brain MRI images into four categories: Glioma, Meningioma, No Tumor, and Pituitary. Built with TensorFlow and Keras, the model achieves high accuracy in detecting brain tumors.

Dataset
The dataset contains brain MRI images organized into:

Training: Images for training.

Testing: Images for evaluation.

Categories:

Glioma

Meningioma

No Tumor

Pituitary

Model Architecture
The CNN architecture includes:

Conv2D layers with ReLU activation.

MaxPooling2D layers.

Dense layers with Dropout for regularization.

Softmax output layer for classification.

Training
Image Size: 150x150

Batch Size: 32

Epochs: 50

Optimizer: Adam

Loss Function: Categorical Cross-Entropy

Data augmentation (rotation, flipping, etc.) is applied to improve generalization.

Results
The model achieves high accuracy on the test dataset. Training and validation accuracy/loss are plotted to visualize performance.
