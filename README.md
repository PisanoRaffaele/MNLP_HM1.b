# 📝 Sentence Classification Project (NLP - University of La Sapienza)

This project, developed as part of the **MNLP** course at the University of **La Sapienza**, focuses on solving a **Sentence Classification** task. The goal is to classify sentences using a LSTM model into two predefined categories: **hateful** and **neutral**. This is an important task in Natural Language Processing (NLP) that can be applied to content moderation and sentiment analysis.

---

## 🔑 Task Overview

In this task, we are required to:

- **Classify sentences** into categories based on their content using a LSTM model-
- **Establish a baseline** model that will serve as a reference point for evaluating more sophisticated models.

---

## 📉 Baseline Approach

A **baseline model** is a simple, naïve approach that solves the problem in a basic way. It provides:

- A **performance benchmark** to assess more complex models.
- A **reference point** to evaluate the effectiveness of sophisticated methods.
- A way to identify **data imbalances** in the given dataset.

In this project, the baseline model will be a simple **LSTM** (Long Short-Term Memory) network. We will evaluate its performance and compare it to more advanced approaches.

---

## 🧠 Model Development

### 1️⃣ **Baseline Model (GRU)**:
   - Initially, the model was built using a **GRU (Gated Recurrent Unit)** architecture, which served as the **baseline** for the task.
   - The GRU was trained on the assigned dataset, and its performance was evaluated as a reference point for comparison.

### 2️⃣ **Improvement with BiLSTM and Early Stopping**:
   - After evaluating the GRU baseline, the model was enhanced by switching to a **BiLSTM (Bidirectional LSTM)** architecture for better handling of contextual information.
   - An **early stopping mechanism** was added to prevent overfitting and improve model generalization.
   - Additionally, **predefined word embeddings** were incorporated to better represent words semantically, resulting in improved model performance.
   - These adjustments led to a noticeable increase in performance over the initial baseline, especially in terms of classification accuracy and overall robustness.

---

## ⚙️ Requirements

- **No Transformers or BERT** models: You should work only with models up to **BiLSTM** (Bidirectional LSTM).
- **No PyTorch Lightning**: The implementation must be done using **standard PyTorch**.
- The **baseline model** will serve as the foundation for subsequent improvements.

