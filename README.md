# 🧠 Small Language Model (SLM) from Scratch using TinyStories

## Overview

This project demonstrates the end-to-end implementation of a decoder-only Small Language Model (SLM) trained from scratch using the TinyStories dataset.

The primary goal of this project was to understand how modern language models are built and trained, including every stage of the pipeline—from dataset preprocessing and tokenization to transformer training and text generation.

Rather than relying on pretrained models, this implementation starts from randomly initialized weights, providing hands-on experience with the complete language model training workflow.

---

## Features

- Training a Small Language Model from scratch
- TinyStories dataset preprocessing
- GPT-2 Byte Pair Encoding (BPE) tokenization using `tiktoken`
- Transformer-based decoder architecture
- PyTorch training pipeline
- Automatic checkpoint saving
- Autoregressive text generation
- Google Colab implementation

---

## Tech Stack

- Python
- PyTorch
- NumPy
- Hugging Face Datasets
- tiktoken
- Google Colab

---

## Dataset

**TinyStories**

TinyStories is a simplified text dataset designed specifically for training small language models while reducing computational requirements compared to large-scale datasets.

Dataset Workflow:

```
TinyStories Dataset
        │
        ▼
Tokenization
        │
        ▼
Training Samples
        │
        ▼
Transformer Model
        │
        ▼
Training
        │
        ▼
Checkpoint Saving
        │
        ▼
Text Generation
```

---

## Project Structure

```
slm-from-scratch-tinystories/

│── TinyStories_SLM_Training.ipynb
│── README.md
│── requirements.txt
│── images/
│── checkpoints/
```

---

## Learning Objectives

This project was built to gain practical experience with:

- Transformer architecture
- Self-attention mechanism
- Tokenization using Byte Pair Encoding
- Language model training
- Batch creation
- Loss optimization
- Gradient updates
- Checkpoint management
- Autoregressive text generation

---

## Results

The model successfully completes the full training pipeline and is capable of generating text.

Due to computational limitations of the free Google Colab environment, the generated text is not yet highly coherent. Training a language model from scratch requires significantly more compute, training iterations, and hyperparameter tuning than were available during this implementation.

This project focuses on understanding and implementing the complete training workflow rather than achieving production-level text quality.

---

## Challenges Faced

During development, several practical challenges were encountered:

- Long training times on Google Colab
- GPU runtime limitations
- Limited number of training iterations
- Training from randomly initialized weights
- Output quality affected by limited computational resources
- Hyperparameter tuning constrained by available hardware

These challenges reflect common issues encountered when training language models from scratch and provided valuable learning experience.

---

## Future Improvements

- Train for significantly more iterations
- Experiment with larger transformer architectures
- Fine-tune learning rate scheduling
- Use mixed-precision training
- Train on higher-performance GPUs
- Improve text generation quality
- Compare results with pretrained transformer models

---

## How to Run

### Clone the repository

```bash
git clone https://github.com/yourusername/slm-from-scratch-tinystories.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the notebook

Open:

```
TinyStories_SLM_Training.ipynb
```

in Google Colab or Jupyter Notebook and execute the cells sequentially.

---

## Key Takeaways

Through this project, I developed a deeper understanding of:

- Transformer-based language models
- Tokenization pipelines
- Deep learning model training
- PyTorch implementation
- Language model optimization
- Challenges involved in training models from scratch

---

## Acknowledgements

- TinyStories Dataset
- Hugging Face Datasets
- OpenAI tiktoken
- PyTorch

---

## Author

**Harnaaz**

If you found this project helpful, feel free to ⭐ the repository.
