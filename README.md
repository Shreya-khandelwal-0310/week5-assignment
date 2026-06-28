# Deep Learning Text Generation using RNN, LSTM and GRU

## 📌 Problem Statement

Design and implement a Deep Learning model capable of learning the underlying structure, grammar, and contextual dependencies of a given text corpus to generate coherent and meaningful text using:

- Vanilla RNN
- LSTM
- GRU

The project compares the performance of these sequence models for next-word prediction and text generation.

---

## 📂 Dataset

A custom text corpus containing sentences related to Artificial Intelligence and Deep Learning is used for training.

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib

---

## 📖 Project Workflow

1. Load and preprocess the text corpus
2. Tokenize the text
3. Create n-gram sequences
4. Pad input sequences
5. Build Vanilla RNN model
6. Build LSTM model
7. Build GRU model
8. Train all models
9. Compare training loss
10. Generate text samples

---

## ⚙ Model Improvements

- Custom text corpus
- Embedding Dimension: **64**
- Hidden Units: **128**
- Epochs: **200**
- Generated **10 words** instead of 5

---

## 📊 Results

- Successfully trained Vanilla RNN, LSTM and GRU models.
- Compared training loss.
- Generated meaningful text samples.
- LSTM and GRU captured long-term dependencies better than Vanilla RNN.

---

## ✅ Conclusion

- Vanilla RNN performs well on short sequences but struggles with long-term dependencies.
- LSTM provides better memory handling through gating mechanisms.
- GRU achieves similar performance with fewer parameters and faster training.
- Increasing embedding size, hidden units and epochs improved generated text quality.

---

## 👩‍💻 Author

Shreya Khandelwal
