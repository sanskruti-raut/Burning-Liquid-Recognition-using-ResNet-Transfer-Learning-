# Flame-Recognition-using-ResNet-Transfer-Learning-
This repository contains code for a flame classification model that can classify images of flames into three categories: ethanol, pentane, and propanol.

# Data Preprocessing
The dataset is organized into train, validation, and test sets with a split ratio of 70%, 15%, and 15% respectively. Images are preprocessed with normalization and augmentation techniques such as rotations, flips, and scaling.

# Model
The model architecture is based on the ResNet-34 convolutional neural network. The final fully connected layer is modified to output predictions for the three flame categories.

# Training
The model is trained using the Adam optimizer with a learning rate of 1e-4 for 20 epochs. During training, the model's performance is evaluated on both the training and validation sets. Adjusted layer freezing and learning rate experiments are conducted for potential performance improvements.

# Results
After training, the model achieves an accuracy of 80.47% on the validation set.

# Layer Visualization
Visualization of intermediate layers of the model is provided for better understanding of feature extraction.

# Analysis
The fine-tuned model is evaluated on a separate test set, achieving an accuracy of 79.57%. A baseline model is also evaluated, providing a comparison metric for the effectiveness of the fine-tuning process.

This README provides an overview of the codebase, its functionalities, and the results obtained. For detailed implementation and usage instructions, please refer to the corresponding code files.
