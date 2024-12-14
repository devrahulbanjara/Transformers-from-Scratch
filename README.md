# Transformers-from-Scratch

This repository contains my implementation of Transformers from scratch using PyTorch. The goal is to understand the inner workings of the Transformer architecture by building it step-by-step, including core components like attention mechanisms, feedforward networks, and positional encodings.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Modules](#modules)
- [Future Plans](#future-plans)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Transformers have revolutionized the field of natural language processing and beyond. This repository is a learning project aimed at developing a deeper understanding of the architecture by implementing it from the ground up, without relying on high-level libraries like Hugging Face.

By building each component manually, I aim to demystify how Transformers work and share insights with others on this journey.

## Features

- Implements core Transformer components:
  - Scaled Dot-Product Attention
  - Multi-Head Attention
  - Positional Encodings
  - Feedforward Neural Networks
  - Layer Normalization
- Built entirely from scratch using PyTorch.
- Fully modular design for easy experimentation and extension.

## Installation

Clone the repository and install the required dependencies:

```bash
https://github.com/devrahulbanjara/Transformers-from-Scratch
cd Transformers-from-Scratch
pip install -r requirements.txt
```

## Usage

Run the main script to test the Transformer implementation:

```bash
python main.py
```

You can also explore individual modules to understand their implementation. Each module is designed to be self-contained for easy reading and experimentation.

## Modules

- `attention.py`: Implements the scaled dot-product attention and multi-head attention mechanisms.
- `positional_encoding.py`: Adds positional encodings to input embeddings.
- `transformer_block.py`: Implements a single Transformer encoder block.
- `transformer.py`: Assembles multiple Transformer blocks into a complete encoder or decoder.
- `main.py`: Demonstrates usage of the Transformer model with a sample task.

## Future Plans

- Add a Transformer Decoder implementation.
- Train the model on small NLP datasets to demonstrate functionality.
- Integrate with a tokenizer for handling raw text input.
- Add visualization tools for attention weights.

## Contributing

Contributions are welcome! If you have suggestions for improvements or additional features, feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
