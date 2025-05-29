# Scalable-multi-class-sentiment-analysis-with-LSTM-TensorFlow-and-Tokenization
Built and scaled up a sentiment classifier on 4 million product reviews using TensorFlow

**📌 Project Summary**

This project applies deep learning techniques—specifically LSTM networks using the TensorFlow framework—to build a multi-class sentiment classifier trained on a dataset of 4 million product reviews. Reviews are categorized into three sentiment classes: negative, neutral, and positive. The model is trained in two stages:

On a subset of 500k reviews for rapid experimentation.

On the full dataset using batched processing to ensure memory efficiency during training.

**📂 Notebooks**

sentiment_subset.ipynb — Training on a 500k sample for faster iteration and experimentation.

sentiment_full_batch.ipynb — Full-scale training on the complete 4M dataset using data batching.

**🧠 Techniques Used**

- Custom Tokenization with TextVectorization

- LSTM-based neural network

- TensorFlow ModelCheckpoint and EarlyStopping

- Performance metrics: accuracy, precision, recall

- Data batching to handle large-scale datasets efficiently

**🚀 Model Architecture**

- Input: Tokenized text reviews

- Embedding Layer

- Bidirectional LSTM

- Dense Layers with Dropout

- Output: Softmax with 3 sentiment classes

**🧪 Results**

Achieved  **84% recall on Negative reviews** and **82% accuracy** on the validation set using 4 M reviews.

Scaled to 4 million reviews with minimal memory overhead via batched processing.

