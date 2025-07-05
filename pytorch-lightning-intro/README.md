# ⚡ Intro to PyTorch Lightning (MNIST Classifier)

This notebook provides a clean and modular implementation of a neural network classifier using **PyTorch Lightning**. It shows how to build, train, and evaluate an MNIST digit classifier while keeping the codebase minimal and scalable.

---

## 📌 What You'll Learn
| Component | Description |
|-----------|-------------|
| `LightningDataModule` | Encapsulates data loading and preprocessing logic |
| `LightningModule` | Contains model architecture, training/validation steps, and optimizer |
| `Trainer` | Runs training loop with built-in callbacks, logging, and evaluation |

---

## 🧰 Dependencies
```bash
pip install pytorch-lightning torchvision torchmetrics
```

---

## 🧪 Model Overview
- Architecture: Simple feedforward neural net
- Input: MNIST digits (28x28 grayscale images)
- Output: 10-class softmax (digits 0–9)
- Metrics: Accuracy, CrossEntropy Loss
- Epochs: 3 (can be extended)

---

## 🌟 Highlights
- 🔁 Reusable code structure for any classification task
- ⚙️ Automatic logging of metrics via `self.log`
- 🔌 Works with GPU/CPU without code changes
- 📦 Easily replace MNIST with any dataset

---

## 🧠 Part of `llm-learning-hub`
This notebook is part of a hands-on engineering series designed to demonstrate clean AI workflows using modern tooling and best practices.

---

## ✨ Author
**Muhammad Taha Nasir** — Engineering scalable AI pipelines with reproducibility and clarity.  
🔗 [linkedin.com/in/muhammadtahanasir](https://linkedin.com/in/muhammadtahanasir)

---

**Train deep learning models with less boilerplate. Focus on ideas, not for-loops.**
