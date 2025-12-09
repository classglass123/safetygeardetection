# Technical Approach

I used two deep learning models: AlexNet and ResNet18.

## Preprocessing
- Images resized to 224×224
- Normalized RGB channels
- Data augmentation:
  - flips
  - rotations
  - brightness changes

## Training
- Loss: Cross-entropy
- Optimizer: Adam
- Learning rate experiments: 0.001 vs 0.0001
- Batch sizes: 16 and 64
- Trained for 5 epochs
- Logged metrics with Weights & Biases (wandb)

## Models
- **AlexNet:** classic CNN with five convolutional layers and three fully connected layers  
- **ResNet18:** deeper network with skip connections

These approaches allowed me to compare simple vs. modern CNN architectures.
