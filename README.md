# 🎬 IMDB Sentiment Classification using Simple RNN

This project demonstrates an **end-to-end deep learning pipeline** for **sentiment analysis** using a **Simple RNN** model on the **IMDB movie review dataset**. It walks through preprocessing, tokenization, embedding, training, and evaluation of a deep learning model for binary classification (positive or negative review).

---

## 📊 Features

- 🧠 Uses a **Simple RNN model** for text classification
- 📚 Loads and processes the IMDB dataset from Keras
- 🔤 Tokenizes and pads sequences using Keras `Tokenizer`
- 📈 Visualizes training loss and accuracy
- 💾 Saves trained model to disk (`imdb_simple_rnn_model.h5`)

---

## 🧰 Tech Stack

- **Python 3.10+**
- **TensorFlow / Keras**
- **NumPy / Matplotlib**
- **Keras Datasets (IMDB)**

---

## 🎯 Problem Statement

Classify IMDB movie reviews as **positive** or **negative** using a sequential deep learning model (Simple RNN). The model is trained on tokenized reviews and evaluated on a separate test set.

---

## 🚀 Installation

**1. Clone the repository**
- git clone https://github.com/Kuntalsvyas/IMDB-Dataset-End-to-end-Deep-Learning-Project-Using-Simple-RNN.git
- cd IMDB-Dataset-End-to-end-Deep-Learning-Project-Using-Simple-RNN

**2. Create a virtual environment**
- python -m venv venv
- source venv/bin/activate  # For Windows: venv\Scripts\activate

**3. Install required libraries**
- pip install -r requirements.txt

**4. Run the training script**
- python imdb_simple_rnn.py

---

# 📈 Model Summary
- Embedding Layer
- SimpleRNN Layer
- Dense output with sigmoid for binary classification

**✅ Achieved good performance with minimal architecture**
**📊 Plots available for accuracy/loss comparison across epochs**

---

# 📌 Future Improvements
 - Replace SimpleRNN with LSTM or GRU
 - Add dropout and regularization
 - Deploy as a Streamlit sentiment classifier
 - Experiment with pretrained word embeddings

---

# 🙌 Author
Created by Kuntal Vyas
If you like this project, don't forget to ⭐ the repo and share it!
