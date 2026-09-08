# Spam vs Ham 📩

A basic Natural Language Processing (NLP) project for classifying messages as **Spam** or **Ham**.

## 📊 Dataset

The project uses an SMS spam dataset containing labeled messages:

- **Spam** — unwanted/promotional messages
- **Ham** — legitimate messages

The dataset is stored in `spam.csv`.

## 🧠 Approaches

### Model Selection

`model_selection.ipynb`

Experiments with different machine learning models for the spam classification task.

### Model Testing

`testing_notebook.ipynb`

Evaluates the selected model using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

### Word2Vec

`using w2vec/word2_vec.ipynb`

Uses **Word2Vec embeddings** to convert text into numerical vector representations before classification.

Current Word2Vec results:

| Metric | Score |
|---|---:|
| Accuracy | ~96% |
| Ham F1 | 0.87 |
| Spam F1 | 0.98 |

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Gensim
- Jupyter Notebook
- Word2Vec

