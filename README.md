# Graph Convolutional Network (GCN) Implementation

## Overview
This repository contains an implementation of a **Graph Convolutional Network (GCN)** for node classification using **PyTorch** and **PyTorch Geometric**. The GCN model is trained on graph-structured data, leveraging graph convolutions to learn node embeddings and classify nodes based on their features and connectivity.

## Features
- Implementation of a **Graph Convolutional Network (GCN)**.
- Uses **PyTorch Geometric** for handling graph data.
- Includes a training loop with loss tracking and accuracy evaluation.
- Logs training metrics for analysis.

## Installation
Ensure you have Python 3.8+ installed. Then, install the required dependencies:

```bash
pip install -r requirements.txt
```

## Results
- The GCN model achieves **high accuracy** on benchmark datasets like Cora.
- The trained embeddings capture structural and feature-based information for each node.

## References
- PyTorch Geometric documentation: [https://pytorch-geometric.readthedocs.io](https://pytorch-geometric.readthedocs.io)

## License
This project is open-source and available under the MIT License.

