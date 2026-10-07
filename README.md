# 📩 SMS Spam Detection using NLP

This project implements a **Spam Detection model** using **Natural Language Processing (NLP)** techniques in Python. The goal is to classify SMS messages as **Spam** or **Ham (Not Spam)** by applying text preprocessing, feature extraction, and machine learning models.  

The dataset used is the **UCI SMS Spam Collection Dataset**, which contains over **5,000 labeled messages**.  

---

## 🚀 Project Overview

1. **Data Collection**  
   - Dataset: [SMS Spam Collection Dataset (UCI Repository)](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)  
   - Contains SMS messages labeled as **spam** or **ham**.  

2. **Data Preprocessing**  
   - Removal of stopwords and punctuation.  
   - Tokenization and stemming/lemmatization.  
   - Conversion of text to **Bag of Words (BoW)** and **TF-IDF** features.  

3. **Exploratory Data Analysis (EDA)**  
   - Distribution of spam vs ham messages.  
   - Message length analysis.  
   - Visualization using **matplotlib** and **seaborn**.  

4. **Modeling**  
   - Implemented a **Naïve Bayes Classifier** for text classification.  
   - Compared performance on BoW and TF-IDF features.  

5. **Evaluation**  
   - Accuracy, Precision, Recall, and F1-Score used as evaluation metrics.  
   - Confusion matrix plotted for performance visualization.  

---

## 🛠️ Technologies Used

- **Programming Language:** Python  
- **Libraries:**  
  - `pandas`, `numpy` – data handling  
  - `matplotlib`, `seaborn` – visualization  
  - `nltk` – text preprocessing  
  - `scikit-learn` – machine learning models  

---

## 📊 Results

- Achieved strong classification performance with **Naïve Bayes**.  
- Demonstrated the effectiveness of **TF-IDF vectorization** over raw Bag-of-Words.  
- Model shows good generalization for detecting spam messages.  

---

## 📂 Project Structure

```
📁 SMS-Spam-Detection
│── notebook.ipynb       # Jupyter Notebook with full analysis & code
│── README.md            # Project documentation
│── requirements.txt     # Dependencies
│── smsspamcollection/   # Dataset folder
```

---

## ⚙️ How to Run

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Officialojih/SMS-Spam-Detection.git
   cd SMS-Spam-Detection
   ```

2. **Create a virtual environment (recommended)**  
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Mac/Linux
   venv\Scripts\activate      # On Windows
   ```

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Download NLTK resources**  
   In a Python shell or notebook, run:  
   ```python
   import nltk
   nltk.download('stopwords')
   nltk.download('punkt')
   ```

5. **Run the Notebook**  
   ```bash
   jupyter notebook notebook.ipynb
   ```

---

## 🎯 Future Work

- Experiment with advanced models (Logistic Regression, SVM, Random Forest).  
- Use **Word Embeddings (Word2Vec, GloVe, BERT)** for improved feature representation.  
- Build a **Streamlit Web App** for real-time SMS spam classification.  

---

## 👨‍🎓 About Me  

I’m **James Ojih (@Officialojih)**, a **Mechatronics Engineering graduate** with a passion for **Data Science, Machine Learning, AI, and Robotics**. This project reflects my journey into NLP and my ability to apply data-driven approaches to real-world problems.  
