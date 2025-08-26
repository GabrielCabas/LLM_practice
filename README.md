# LLM Practice Project

This repository is based on the book [Build a Large Language Model (From Scratch)](https://github.com/rasbt/LLMs-from-scratch) by Sebastian Raschka.

## 🎯 Project Goal

I'm learning to build Large Language Models from the ground up by reproducing examples from the book and explaining the concepts to myself as a form of self-teaching. This hands-on approach helps me understand the fundamental principles behind modern LLMs.

## 📚 What We're Learning

This project covers the core components of transformer-based language models:

- **Tokenization**: Byte Pair Encoding (BPE), WordPiece, and other tokenization strategies
- **Embeddings**: Word embeddings, positional encoding, and layer normalization
- **Attention Mechanisms**: Multi-head attention, scaled dot-product attention
- **Transformer Architecture**: Encoder-decoder structure, feed-forward networks
- **Training**: Loss functions, optimization, and training loops
- **Inference**: Text generation and sampling strategies

## 🏗️ Project Structure

```
LLM_practice/
├── README.md
├── requirements.txt
├── src/
│   ├── __init__.py
│   ├── tokenization/
│   │   ├── __init__.py
│   │   ├── basic_tokenizer.py
│   │   └── bpe_tokenizer.py
│   ├── models/
│   │   ├── __init__.py
│   │   ├── attention.py
│   │   ├── embeddings.py
│   │   └── transformer.py
│   ├── utils/
│   │   ├── __init__.py
│   │   └── data_loader.py
│   └── training/
│       ├── __init__.py
│       └── trainer.py
├── notebooks/
│   ├── 01_tokenization_examples.ipynb
│   ├── 02_attention_visualization.ipynb
│   └── 03_training_demo.ipynb
├── tests/
│   ├── __init__.py
│   ├── test_tokenization.py
│   └── test_models.py
└── data/
    └── sample_texts/
```

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- pip or conda

### Installation
```bash
# Clone the repository
git clone <your-repo-url>
cd LLM_practice

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### Running Examples
```bash
# Run tests
python -m pytest tests/

# Start Jupyter notebooks
jupyter notebook notebooks/
```

## 📖 Learning Path

1. **Phase 1: Foundations**
   - Basic tokenization concepts
   - Simple embedding implementations
   - Understanding attention mechanisms

2. **Phase 2: Core Components**
   - Multi-head attention implementation
   - Positional encoding
   - Feed-forward networks

3. **Phase 3: Architecture**
   - Complete transformer blocks
   - Encoder-decoder structure
   - Model initialization

4. **Phase 4: Training & Inference**
   - Loss functions and optimization
   - Training loops
   - Text generation

## 🔧 Dependencies

- **PyTorch**: Deep learning framework
- **NumPy**: Numerical computing
- **Matplotlib**: Visualization
- **Jupyter**: Interactive notebooks
- **Pytest**: Testing framework

## 📝 Notes & Observations

As I work through each component, I'll add my own explanations and insights here:

- **Key Insights**: What I learned from each implementation
- **Common Pitfalls**: Mistakes I made and how to avoid them
- **Optimizations**: Ways to improve the code
- **Questions**: Things I'm still figuring out

## 🤝 Contributing

This is a personal learning project, but feedback and suggestions are welcome! Feel free to:
- Point out errors or improvements
- Suggest additional resources
- Share your own implementations

## 📚 Resources

- [Original Book Repository](https://github.com/rasbt/LLMs-from-scratch)
- [Attention Is All You Need Paper](https://arxiv.org/abs/1706.03762)
- [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)

## 🎯 Current Status

- [x] Project setup and README
- [ ] Basic tokenization implementation
- [ ] Attention mechanism implementation
- [ ] Transformer architecture
- [ ] Training pipeline
- [ ] Text generation

---

*Learning by doing, one component at a time! 🚀*