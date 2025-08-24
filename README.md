
# Sentiment Analysis of Product Reviews

This project performs sentiment analysis on a dataset of product reviews using machine learning techniques. It is implemented in a Google Colab notebook and is designed to classify reviews as positive or negative.

## 📁 Project Structure
```
Sentiment-Analysis-Product-Reviews/
│
├── data/
│   └── reviews.csv
│
├── model/
│   └── (trained models and related files)
│
└── Sentiment_Analysis_Notebook.ipynb
```

## 📊 Dataset
- **File**: `reviews.csv`
- **Description**: Contains product reviews and their associated sentiment labels.
- **Source**: Uploaded manually to the `data/` folder in Google Drive.

## 🚀 How to Run
1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Mount your Google Drive to access the dataset:
```python
from google.colab import drive
drive.mount('/content/drive')
```
3. Navigate to the project folder and load the dataset.
4. Run each cell sequentially to preprocess data, train the model, and evaluate performance.

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Google Colab

## 📈 Model Overview
- Text preprocessing (tokenization, stopword removal)
- Feature extraction using TF-IDF
- Classification using Logistic Regression / Naive Bayes

## 🧠 Model Folder
A `model/` directory has been added to the project to store trained models, configuration files, and checkpoints. This helps organize and preserve your machine learning artifacts for future use or deployment.

## 💡 Future Enhancements
- Use deep learning models like LSTM or BERT
- Add visualizations for sentiment distribution
- Deploy model using Flask or Streamlit

## 📬 Contact
For questions or suggestions, feel free to reach out via GitHub Issues.
