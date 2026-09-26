# Tifinagh Multiclass Classification using MLP

This project implements a Multilayer Perceptron from scratch using NumPy
for handwritten Tifinagh character classification.

## Dataset
- 33 Tifinagh classes
- Images resized to 32x32
- 25,740 images used

## Architecture
1024 -> 64 -> 32 -> 33

- ReLU activation
- Softmax output
- Cross-Entropy Loss
- Mini-batch Gradient Descent

## Training
- Learning rate: 0.01
- Batch size: 32
- Epochs: 100

## Results
- Training Accuracy: 85.99%
- Validation Accuracy: 83.61%
- Test Accuracy: 83.64%

## Files
- `TP2_Tifinagh_MLP.ipynb`
- `rapport_tifinagh_ameliore.tex`
- `confusion_matrix.png`
- `loss_curve.png`
- `accuracy_curve.png`
