🛑 Traffic Sign Classification using Transfer Learning (VGG16)
This project implements a deep learning-based traffic sign classification system using transfer learning with the pre-trained VGG16 model. Designed to support autonomous vehicle systems, the model accurately classifies traffic signs from image data and achieved strong performance on test data.

🔍 Key Features:
Utilized VGG16 (pre-trained on ImageNet) as a base model for feature extraction.

Customized the classifier head with Dense, Dropout, and sigmoid activation layers for binary classification.

Applied data augmentation (rotation, zoom, shifts, flips) using ImageDataGenerator to boost generalization.

Achieved high accuracy on both training and validation sets (replace with actual metrics from your final cell).

📂 Dataset:
The dataset is structured into train/test directories with labeled subfolders for each class.

Image resolution resized to 224x224 to match VGG16 input format.

🛠 Tech Stack:
TensorFlow & Keras for model building and training.

VGG16 from keras.applications for transfer learning.

OpenCV (if used later for real-time inference).

Google Colab for training and experimentation.

🚗 Use Case:
Perfect for autonomous driving and driver assistance systems to recognize and respond to road signs in real-time.
