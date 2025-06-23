# 🎬 Movie Review Sentiment Analysis

This project uses an LSTM model to predict whether a movie review is **Positive** or **Negative**, based on the [IMDB 50K Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews).

---

## 📌 What the project does

- Loads 50,000 movie reviews.
- Cleans and preprocesses the text.
- Visualizes the data using word clouds and plots.
- Trains a **Bidirectional LSTM** model.
- Evaluates the model's performance.
- Saves the model in `.h5`, `.keras`, and `.tflite` formats.
- Predicts sentiment for custom text inputs.

---

## 🛠️ Requirements

```bash
pip install pandas numpy seaborn matplotlib contractions nltk tensorflow wordcloud beautifulsoup4
````

---

## 🚀 How to run

1. Clone the repo:

```bash
git clone https://github.com/ranaehelal/Movie-Review-Sentiment.git
```

2. Open the script or notebook and run step by step.

---

## 🧠 Example Output

```python
predict_sentiment("This movie was amazing!")
# {'label': 'Positive', 'score': 0.91}

predict_sentiment("It was boring and too long.")
# {'label': 'Negative', 'score': 0.12}
```

