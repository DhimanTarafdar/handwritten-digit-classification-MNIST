# Handwritten Digit Classification using ANN (PyTorch)

A simple Artificial Neural Network built with PyTorch to classify handwritten digits from the MNIST dataset.

## What this project does

- Loads the MNIST dataset (70,000 images of handwritten digits 0–9)
- Builds a 3-layer ANN using PyTorch
- Trains the model and tracks loss each epoch
- Evaluates accuracy on test data
- Predicts the label of a single image

## Model Architecture

```
Input (784) → Linear → ReLU → Linear → ReLU → Linear → Output (10)
                            
```

## Libraries Used

- `torch` — build and train the neural network
- `torchvision` — load the MNIST dataset
- `matplotlib` — visualize images

## How to Run

1. Open the notebook in Google Colab
2. Run all cells from top to bottom
3. That's it!

## Results

The model achieves around **97% accuracy** on the test set after 100 epochs.

## Reference

This notebook follows the same style as the Fashion MNIST PyTorch notebook, just applied to handwritten digit classification.

