# Notes: NLP in Deep Learning

## Overview:

- The video discusses the application of **NLP in deep learning**.
- Previous topics in NLP related to machine learning included:
  - One-Hot Encoding
  - Bag of Words
  - TF-IDF
  - Word2Vec
  - Average Word2Vec
- Practical applications discussed:
  - Sentiment Analysis
  - Text Classification

---

## Neural Networks and Tabular Data:

- **Artificial Neural Networks (ANN)** were primarily used for **classification** and **regression** tasks with **tabular data**.
- **Tabular data** examples:
  - **House Price Prediction**: Features like house size, number of rooms, and price were used to predict house prices (a regression problem).
- **Important Characteristics of Tabular Data**:
  - Sequence of data **does not matter** in tabular data.
  - Changing the order of features like `f1`, `f2` does not impact the training process.

---

## Convolutional Neural Networks (CNN) and Images:

- **CNN** is commonly used for:
  - **Image Classification**
  - **Object Detection**
- Examples:
  - Higher variants like **R-CNN**, **YOLO**, etc.

---

## Sequential Data and NLP:

- When moving to **NLP in Deep Learning**, we deal with **sequential data**.
- **Sequential Data**: Data where the order of information matters.
  - Examples:
    - **Text Generation**: Generating the next word in a sequence.
    - **Chatbot Conversations**: Context of the conversation is important.
    - **Language Translation**: Translating between languages while preserving the sequence.
    - **Auto-Suggestion**: Used in applications like LinkedIn, Gmail, etc.
    - **Sales Data**: Sequence of sales data over time used for **sales forecasting**.

---

## Sequential Data:

- **Sequential data** refers to data where the order of the elements matters, such as:
  - **Text**: The order of words matters in conveying meaning.
  - **Sales Data**: The sales figures over time matter for predictions like **sales forecasting**.

### Key Examples of Sequential Data:

- **Text Generation**: Predicting the next word in a sentence.
- **Chatbot Conversations**: Responding based on the sequence of questions and answers.
- **Language Translation**: Converting sentences from one language to another, preserving the order.
- **Sales Forecasting**: Predicting future sales based on past sales patterns.

---

## Can We Use ANN to Solve Sequential Data Problems?

- **ANN** was used to solve problems with tabular data, but for sequential data, the sequence is important.
- The question raised: **Can we use ANN to solve problems with sequential data?**
  - This will be discussed in the next session.

---

## Upcoming Topics in NLP in Deep Learning:

- Topics that need to be covered in **NLP in deep learning**:
  1. **Simple RNN (Recurrent Neural Networks)**
  2. **LSTM (Long Short-Term Memory)** and **GRU (Gated Recurrent Units)**
  3. **Bidirectional RNN**
  4. **Encoders and Decoders**
  5. **Self-Attention**
  6. **Transformers**

---

## Generative AI and NLP:

- **Generative AI** and **LLMs (Large Language Models)** are currently trending.
- Understanding the architectures of **neural networks for NLP** is crucial for working with **LLMs**.
  - **Transformers** form the backbone of many modern generative AI models.
  - **LLM models** like **OpenAI's models** are built on these architectures.

---

## Conclusion:

- The session introduced the basics of **NLP in deep learning**.
- Key prerequisites for working with **generative AI**:
  - Understanding of RNN, LSTM, GRU, transformers, and self-attention mechanisms.
  - Practical problem-solving using these architectures.
- The next session will address whether **ANN** can solve sequential data problems.
