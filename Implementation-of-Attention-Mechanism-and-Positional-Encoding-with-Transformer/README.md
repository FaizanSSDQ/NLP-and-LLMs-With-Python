# Transformer Basics: Self-Attention and Positional Encoding Lab

## Overview
This project is a hands-on lab exploring the foundational elements of the Transformer architecture, focusing on **self-attention mechanisms** and **positional encoding**. It demonstrates how these components enable transformers to process textual data effectively for tasks like translation or text processing. The lab provides both theoretical understanding and practical implementation, targeting beginners in NLP and deep learning.

I have implemented a basic word-to-word translator using a simple translational dictionary. Then I have implemented transformer using Encoder Layers architecture. 

**Note:** The main file of this project is `"Attention Mechanism and Positional Encoding.ipynb"`. Rest of the files in the directory are either for practice or irrelevant to the project.

## Objectives
If you follow this notebook as it is, you would be able to:
- Understand the basics of **tokenization** and how textual data is prepared for neural network models.
- Learn the concept of **one-hot encoding** and its role in representing text for machine learning.
- Explore the **self-attention mechanism**, a core component of transformers, which dynamically focuses on different parts of the input sequence.
- Implement a basic **self-attention mechanism** and integrate it into a neural network model.
- Grasp the importance of **positional encoding** in transformers, providing sequence order information.
- Implement **positional encoding** and observe its impact on model performance and sequence understanding.
- Apply these concepts to build a simple **translation model or text processing task**.
- Develop intuition for modern NLP models, particularly transformers, and their advantages over traditional models like RNNs and LSTMs.
- Encourage further exploration of model architectures, hyperparameters, and NLP applications.

## What Was Done
- **Tokenization:** Implemented a basic tokenizer to preprocess text into tokens.
- **One-Hot Encoding:** Created a simple representation of tokens as one-hot vectors.
- **Self-Attention Mechanism:** Built and integrated a self-attention layer to weigh input token relationships.
- **Positional Encoding:** Added sine/cosine-based positional encodings to embeddings.
- **Toy Task:** Applied these components to a small text-processing task (e.g., sequence reversal or translation).
- **Comparison:** Discussed how transformers improve on RNNs and LSTMs via parallel processing and global context.

## Self-Attention Explained
Self-attention is a mechanism in neural networks that allows the model to focus on different parts of the input when generating outputs. It’s a cornerstone of the Transformer architecture, used in NLP tasks like machine translation, text summarization, and sentiment analysis. 

The idea is to let the model weigh the importance of each input token for every output token. This is achieved by:
- Computing a **weighted sum** of input tokens.
- Determining weights via **relationships between all pairs of tokens**, using queries, keys, and values.
- Enabling **dynamic focus**, unlike the fixed receptive fields of CNNs or sequential processing of RNNs.

For example, in "The cat sat," self-attention might emphasize "sat" when processing "cat," capturing contextual dependencies efficiently.

## Requirements
- Python 3.8+
- NumPy (for core implementations)
- (Optional) PyTorch or TensorFlow (for extensions)
- Basic knowledge of neural networks and Python

## References
- "Attention is All You Need" (Vaswani et al., 2017)
- NLP tutorials on tokenization, attention, and transformers

## Author:


[Faizan Saleem Siddiqui](https://www.linkedin.com/in/faizan-saleem-siddiqui-4411bb247?originalSubdomain=pk) is a research scholar, freelancer and AI/ML Engineer.


