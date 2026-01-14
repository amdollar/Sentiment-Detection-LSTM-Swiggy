Sentiment-LSTM-Swiggy
LSTM-based sentiment detection on food-delivery reviews (Swiggy dataset).
This project demonstrates text preprocessing, tokenization, padding, LSTM modeling and evaluation for binary sentiment classification using Keras / TensorFlow.

🔍 Project Overview
Task: Binary sentiment classification (Positive / Negative) from customer reviews.
Dataset: swiggy.csv (columns include Review, Avg Rating).
Labeling rule used in the notebook: Sentiment = 1 if Avg Rating > 3.5 else 0 — note this may create noisy labels.
Model: Embedding -> LSTM -> Dense (sigmoid) trained with binary crossentropy.
Outputs: training history, classification report, confusion matrix and a prediction helper function (make_prediction).
📂 Files (key)
15RNN_LSTM_SentimentGenerationDetection.ipynb — main notebook (preprocessing, model, eval, inference)
swiggy.csv — dataset used by the notebook (keep or provide download instructions)
requirements.txt / SETUP_GUIDE.md — environment notes (use Python 3.12 for TensorFlow compatibility)
🛠️ Setup & Run (quick)
Recommended Python: 3.12 (TensorFlow support)

Create and activate a venv:
Windows (PowerShell)
Install dependencies:
If using Python < 3.12, install TensorFlow separately:
Open 15RNN_LSTM_SentimentGenerationDetection.ipynb in VSCode / Jupyter and run cells.
Use make_prediction(review) (notebook helper) to get quick inference on single reviews.


Anurag Awasthi
