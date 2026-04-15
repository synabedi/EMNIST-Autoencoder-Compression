# EMNIST Image Compression: ANN vs CNN Autoencoders

This project explores image compression using Autoencoders built with PyTorch. I compared two architectures (ANN and CNN) across different bottleneck sizes to see which is more efficient at reconstructing handwritten characters.

## Key Results
* **CNN Superiority:** The Convolutional model achieved a much lower Mean Squared Error (MSE) than the ANN when restricted to the same bottleneck size.
* **Winner:** CNN Design 1 (B-64) reached an MSE of **0.0015**.
* **Efficiency:** CNNs proved to be better at capturing shapes (edges/curves) than simple linear layers.

## Architectures
1. **ANN:** Linear layers with ReLU activation and a Sigmoid output.
2. **CNN:** Convolutional and Transpose Convolutional layers for spatial feature learning.

## How to use
1. Clone the repo.
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook in Jupyter and run all cells.
