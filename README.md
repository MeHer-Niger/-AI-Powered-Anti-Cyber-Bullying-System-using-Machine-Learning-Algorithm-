# 🛡️ Bangla Cyberbullying Detection using NLP & Machine Learning

This project implements a machine learning pipeline to detect cyberbullying in Bangla-language text using Natural Language Processing (NLP). The dataset is preprocessed and analyzed before being passed to multiple classifiers including Naive Bayes, Support Vector Machines, and Logistic Regression.

---

## 📂 Dataset

- **Title**: Bangla Cyberbullying Dataset
- **Author**: [Meheniger (Kaggle)](https://www.kaggle.com/meheniger)
- **Format**: Excel (.xlsx)
- **Description**: A custom-curated dataset containing Bangla text samples labeled as bullying or non-bullying. Designed to address the lack of Bangla-language cyberbullying detection data.
- **Link**: [View on Kaggle](https://www.kaggle.com/meheniger)

---

## 📌 Features

- Custom preprocessing for Bangla text (e.g., foreign character removal, punctuation cleaning)
- Vectorization using CountVectorizer and TF-IDF
- Multiple model evaluation: Naive Bayes, SVM, Logistic Regression
- Performance metrics: Accuracy, Classification Report, Cohen's Kappa
- Visualizations with Plotly and Matplotlib

---

## 🧪 Technologies Used

- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas / NumPy
- Matplotlib / Plotly
- Jupyter Notebook

---

## 🚀 How to Run

1. **Install required packages**
   ```bash
   pip install pandas numpy scikit-learn tensorflow plotly openpyxl
2. Place the dataset file Ensure Bangla Cyberbullying Dataset.xlsx is in the project root or update the file path in the code.
3. Run the notebook Open Final_project.ipynb and run the cells sequentially.

--- 

## 📊 Sample Output

- Text Cleaning Examples
- Accuracy Scores
- Classification Reports for each model
- Cohen Kappa Scores

---

## 🧠 Future Work

- Extend to deep learning-based models like BiLSTM or BERT for Bangla
- Deploy as a web API or app for real-time text classification
- Add more class labels for multi-class detection

--- 

## 📜 License

This project is licensed under the MIT License.

---

## ✍️ Author

Meheniger – Creator of the dataset and developer of the classification pipeline
🔗 Kaggle Profile
