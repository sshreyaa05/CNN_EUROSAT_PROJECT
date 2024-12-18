## Satellite Image Classification Using CNN with MobileNetV2 as Base Model on EuroSAT Dataset
### Project Overview
This project aims to classify satellite imagery from the EuroSAT dataset using Convolutional Neural Networks (CNNs) with MobileNetV2 as the base model. The base model was frozen during training, and preprocessing techniques such as resizing and normalization were applied to ensure optimal input preparation. The final model achieved a test accuracy of 81%.
### Objectives
1. Preprocessing and normalizing EuroSAT dataset images for better model performance.
2. Utilizing MobileNetV2 as a frozen pre-trained base model for transfer learning.
3. Training a CNN classifier to predict satellite image classes.
### Data Preprocessing
1. Resizing Images:
All EuroSAT images were resized to fit the input dimensions expected by MobileNetV2.
2. Normalization:
Pixel values were normalized (scaled between 0 and 1) to ensure stable and uniform CNN training.
These preprocessing steps improved the model's ability to learn patterns from the data efficiently.
### Model Architecture
The CNN model used MobileNetV2 as the pre-trained base model.
1. Frozen Base Model: Only the top layers were trained, while the pre-trained MobileNetV2 layers remained unchanged.
2. This approach utilized transfer learning, leveraging the pre-trained weights for feature extraction.
### Results
After training the CNN using the frozen MobileNetV2 base model, the model achieved a test accuracy of 81%. This demonstrates effective generalization on unseen EuroSAT test data.
### Conclusion
The CNN model successfully classified satellite images from the EuroSAT dataset with 81% test accuracy using MobileNetV2 as the frozen base model. Preprocessing steps like resizing and normalization, combined with transfer learning, contributed to this performance.

