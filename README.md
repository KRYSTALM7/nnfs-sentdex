# Neural Networks from Scratch — sentdex

> Following [sentdex's Neural Networks from Scratch](https://nnfs.io/) series, building every layer of a neural network step by step in pure Python.

I push new code **every day** as I work through the book and video series. No shortcuts — understanding everything from the math up.

---

## Repository Structure

```
nnfs-sentdex/
├── chapters/        # Code from each chapter, organized by topic
├── notes/           # Personal notes & key takeaways
├── requirements.txt # Dependencies (numpy, matplotlib, nnfs)
└── README.md
```

---

## Progress

| Chapter | Topic |
|---------|-------|--------|
| Ch. 1 | Intro & Setup |
| Ch. 2 | Coding Our First Neurons |
| Ch. 3 | The Dot Product |
| Ch. 4 | Batches, Layers, and Objects |
| Ch. 5 |Hidden Layer Activation Functions|
| Ch. 6 |Softmax Activation|
| Ch. 7 |Calculating Loss with Categorical Cross-Entropy|
| Ch. 8 |Implementing Loss |
| Ch. 9 | Introducing Optimization and derivatives |
| Ch. 10+ | ... | 

> I update this table as I make progress. A new commit = a new day of learning.

---

## Setup

```bash
git clone https://github.com/KRYSTALM7/nnfs-sentdex.git
cd nnfs-sentdex
pip install -r requirements.txt
```

**Dependencies:**
- `numpy` — matrix math & dot products
- `matplotlib` — visualizations
- `nnfs` — sentdex's helper package (spiral dataset etc.)

---

## Why This Repo?

Most ML frameworks abstract away what's actually happening — this series tears it all down and rebuilds it from first principles. No PyTorch, no TensorFlow. Just Python and numpy.

Topics covered across the series:
- Forward passes through dense layers
- Activation functions (ReLU, Softmax, Sigmoid)
- Loss calculation (Categorical Cross-Entropy, Binary CE, MSE)
- Backpropagation & gradient computation
- Optimizers (SGD, AdaGrad, RMSProp, Adam)
- Regularization (L1/L2, Dropout)
- Model evaluation & saving

---

## Resources

- Book: [nnfs.io](https://nnfs.io/)
- YouTube: [sentdex — Neural Networks from Scratch](https://www.youtube.com/playlist?list=PLQVvvaa0QuDcjD5BAebJ80kGH4vNYNxRS)

---

## Author

**Sujan** — [@KRYSTALM7](https://github.com/KRYSTALM7)

Learning ML from the ground up, one commit at a time.
