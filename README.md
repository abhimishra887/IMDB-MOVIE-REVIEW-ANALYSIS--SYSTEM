
# 🎬 IMDB Movie Review Sentiment Analysis System

This project is a deep learning-based sentiment analysis system that classifies IMDB movie reviews as **positive** or **negative**. It utilizes an LSTM (Long Short-Term Memory) neural network model built with **TensorFlow/Keras**, and the interface is powered by **Gradio** to provide real-time predictions via a simple web UI.

---

## 🚀 Features

- Sentiment analysis of IMDB movie reviews
- Preprocessing and tokenization of textual data
- LSTM model trained on real review data
- Gradio-powered user interface for live predictions
- Easily extendable and customizable

---

## 🧠 Tech Stack

- **Python**
- **TensorFlow / Keras**
- **LSTM (RNN)**
- **Pandas & NumPy**
- **Gradio** (for UI)
- **Joblib** (for saving/loading tokenizer)
- **Sklearn** (for data splitting)

---

## 📂 Project Structure

```
IMDB-Movie-Review-Sentiment-Analysis/
│
├── model.h5                                                 # Trained LSTM model
├── tokenizer.pkl                                            # Tokenizer for preprocessing
├── IMDB Dataset.csv                                         # Dataset used for training
├── Model_Testing_&_Web_Application.ipynb                    # Gradio app script
├── requirements.txt                                         # Python dependencies
└── README.md                                                # Project documentation
```

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/IMDB-Movie-Review-Sentiment-Analysis.git
cd IMDB-Movie-Review-Sentiment-Analysis
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Application

```bash
python Model_Testing_&_Web_Application.ipynb
```

> This will launch a Gradio interface in your browser where you can enter a movie review and see its sentiment.

---

## 🧪 Example

**Input Review**:  
```
This movie was a visual masterpiece and emotionally powerful!
```

**Predicted Sentiment**:  
```
positive
```

---

## 📈 Model Overview

- Model Type: Sequential LSTM
- Embedding Layer: `input_dim=5000`, `output_dim=128`, `input_length=200`
- LSTM Layer: 128 units with dropout
- Output Layer: Dense with sigmoid activation
- Loss Function: `binary_crossentropy`
- Optimizer: `adam`
- Accuracy: ~87% on test set

---

## ✅ Requirements

```
pandas
numpy
tensorflow
keras
scikit-learn
joblib
gradio
```

(Already included in `requirements.txt`)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

