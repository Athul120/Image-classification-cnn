Image Classification using Convolutional Neural Networks
Project Overview
This project focuses on classifying images of cats and dogs using Convolutional Neural Networks (CNNs). The model is trained on a labeled dataset and achieves high accuracy in distinguishing between the two categories.

Task: Binary Classification - Cats vs Dogs

Model: Custom CNN architecture with convolutional, batch normalization, and dense layers

Dataset: 18,000 images (80% training / 20% validation)

Training Epochs: 15

For a detailed explanation of the methodology and architecture, refer to the project report and source code.

Model Architecture & Training Details
Convolution Layers
3x3 filters with Batch Normalization

Output Channels:

Layer 1: 32

Layer 2: 64

Layer 3: 96

Layer 4: 96

Layer 5: 64

Dense Layers
Fully Connected Layers:

256 → 128 → 2 (output)

Dropout:

Layer 1: 0.2

Layer 2: 0.3

Training Performance
Training Loss: 0.0638

Training Accuracy: 97.59%

Validation Loss: 0.3255

Validation Accuracy: 90.44%

Results & Visualization
The model was evaluated on multiple image sets.



    


