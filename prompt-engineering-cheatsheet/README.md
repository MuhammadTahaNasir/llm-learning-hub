# 🤖 Prompt Engineering Cheatsheet (LLM Patterns from a Big Tech Perspective)

This notebook distills years of hands-on LLM experimentation into a **cheatsheet of prompt patterns** — built by an AI Engineer aspiring toward **production-level AI systems** like those in Big Tech.

It leverages `flan-t5-base` from HuggingFace Transformers, running **100% free** on Colab.

---

## 💡 Why Prompt Engineering Matters
In companies like OpenAI, Meta, and Google, **prompt design** often beats parameter tuning. This repo captures:

- Practical patterns used in LLM-backed systems
- Zero-dependency workflows
- Free-tier deployability (no API costs)

---

## 🧪 Patterns Covered
| # | Pattern | Real-World Use Case |
|--|---------|---------------------|
| 1 | **Zero-shot** | Fast inference without examples |
| 2 | **Few-shot** | Examples embedded in prompt to guide generation |
| 3 | **Instruction** | Task-style commands (great for alignment) |
| 4 | **Chain of Thought** | Logical reasoning & math chains |
| 5 | **Role-based Prompting** | Set persona (e.g., doctor, lawyer, teacher) |
| 6 | **Stylistic/Format Control** | Email tones, formal/informal speech |
| 7 | **Structured Output (JSON)** | Backend-compatible response structuring |

---

## 🛠️ Stack
- `transformers` by HuggingFace 🤗
- Model: `google/flan-t5-base`
- Runtime: Colab Free Tier (no API key, no GPU needed)

---

## 🔧 How to Run
1. Open in [Google Colab](https://colab.research.google.com)
2. Click ▶️ on each cell to run prompt types
3. Try swapping in models like `tiiuae/falcon-rw-1b`, `mistralai/Mistral-7B-Instruct` (via Transformers or HuggingFace Hub)

---

## 🧠 Use This Cheatsheet For:
- LLM product prototyping
- Evaluation of prompt structures before fine-tuning
- Internal tooling for AI assistants or chatbots
- Experimentation logs before system deployment

---

## 🧩 This is Part Of:
**`llm-learning-hub`**: A curated collection of FREE, production-style LLM notebooks:

- ✅ RAG with FAISS & local models
- ✅ Prompt engineering patterns
- ✅ LLM fine-tuning with HuggingFace
- ✅ LLM eval tools + metrics
- ✅ YOLOv8 vision detection pipeline

---

## 🧑‍💻 About the Author
> Building this as part of my roadmap to becoming an **AI Engineer** focused on GenAI systems, RAG architectures, and open-source LLM deployment. Inspired by production best practices from FAANG & top AI labs.

Feel free to ⭐ the repo and fork if you find this valuable!
