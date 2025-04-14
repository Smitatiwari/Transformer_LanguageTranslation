# Transformer_LanguageTranslation

Using the PyTorch deep learning framework, this project implements a **Transformer model** for translating sentences between two languages. Inspired by the original [Attention Is All You Need](https://arxiv.org/abs/1706.03762) paper, it demonstrates the core components of the Transformer architecture for sequence-to-sequence translation tasks.

---

##  Project Objectives

- Build a Transformer model from scratch using TensorFlow.
- Train the model on a parallel corpus (e.g., English–German or English–French).
- Perform sentence translation using the trained model.
- Demonstrate attention mechanisms and token-level translation.

---

##  Model Overview

The Transformer model includes the following components:

- **Positional Encoding** – Adds order information to word embeddings.
- **Multi-Head Attention** – Allows the model to jointly attend to information from different representation subspaces.
- **Encoder & Decoder Stacks** – Deep stacks of self-attention and feed-forward layers.
- **Masking Mechanism** – Prevents attending to future tokens during decoding.
- **Greedy or Beam Search Decoding** – Generates translations during inference.

---

## Sample Output

### Input Sentence (English):
   
   "How are you?"

### Translated Sentence (German/French):

   "Wie geht es dir?" (German)


### Attention Visualization:
Visual representations of attention weights across different heads show which source words the model focuses on when predicting each target word.

---

## Training Details

- **Framework**: TensorFlow 2.x
- **Loss Function**: Cross-Entropy Loss (with padding mask)
- **Optimizer**: Adam with warm-up learning rate schedule
- **Training Epochs**: Configurable (commonly 10–20)
- **Evaluation**: BLEU score for translation accuracy

---

## Evaluation Results

![image](https://github.com/user-attachments/assets/6a6b358e-0d6b-426e-871e-26e76ac95b20)

   
