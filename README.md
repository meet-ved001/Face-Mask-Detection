**Face Mask Detection Model**
This repository contains a deep learning model designed to detect whether individuals are wearing face masks or not. The model uses a pre-trained MobileNetV2 architecture, fine-tuned with a custom head for classification, and is trained on a dataset of images categorized into two classes: "with_mask" and "without_mask."

**Key Features:**
Data Augmentation: The training dataset is augmented using techniques such as rotation, zoom, and horizontal flipping, which helps improve the model's generalization capability.
Transfer Learning: The model leverages MobileNetV2, a lightweight pre-trained convolutional neural network (CNN) trained on the ImageNet dataset, as the base model, which allows for fast and efficient training.
Binary Classification: The model classifies images into two categories: "with_mask" and "without_mask."
High Accuracy: Achieved an impressive **99% accuracy** on the testing set, demonstrating the model's effectiveness in real-world face mask detection tasks.
**Dataset**:
The model was trained on a custom dataset containing images of people with and without face masks.
The dataset was split into training and testing sets with a ratio of 80% for training and 20% for testing.
**Usage**:
The model is saved in .h5 format as mask_detector1.model.h5, making it easy to deploy for real-time face mask detection applications.

![image](https://github.com/user-attachments/assets/0e0fb57e-659c-4a65-b660-92c5baa62609)

**Training Loss and Accuracy Plot:**

![image](https://github.com/user-attachments/assets/db4d9284-a390-4d80-ad3d-d64aa6d8594f)

