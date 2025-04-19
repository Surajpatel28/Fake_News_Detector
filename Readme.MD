# Fake News Prediction 🚨

&#x20;


## 📖 Table of Contents

1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Features & Preprocessing](#features--preprocessing)
4. [Modeling](#modeling)
5. [Evaluation](#evaluation)
6. [Installation](#installation)
7. [Usage](#usage)
8. [Results](#results)
9. [Project Structure](#project-structure)
10. [Future Work](#future-work)
11. [Contributing](#contributing)
12. [License](#license)

---

## 🌟 Overview

Fake News Prediction is a machine learning project that classifies whether a news article is **Real** or **Fake**.It uses a Logistic Regression model. 

**Key Highlights:**

- Text preprocessing with NLTK (stopword removal, stemming).
- Feature extraction via TF-IDF vectorization.
- Classification using Scikit-Learn’s Logistic Regression.
---

## 📂 Dataset

The dataset is sourced from a publicly available fake news dataset and is split into training and test sets.

- **Location:** `dataset/train.csv`
- **Columns:**
  - `id` — Unique identifier for each article.
  - `title` — Headline of the news article.
  - `author`— Author of the news article.
  - `text` — Full text of the news article.
  - `label` — Target variable (0 = Real, 1 = Fake).

> **Note:** Ensure the `dataset/` folder is in the same directory as the notebook for correct path resolution.

---

## 🛠️ Features & Preprocessing

1. **Cleaning & Normalization:**
   - Lowercasing
   - Removal of punctuation and non-alphanumeric characters
2. **Tokenization & Stopword Removal:**
   - NLTK’s English stopwords list
3. **Stemming:**
   - Porter Stemmer from NLTK
4. **Feature Extraction:**
   - TF-IDF Vectorizer with uni-grams and bi-grams

## 🤖 Modeling

- **Algorithm:** Logistic Regression
- **Library:** Scikit-Learn

---

## 📊 Evaluation

> **Sample Metrics:**
>
> - Accuracy on training data : 98.63%
> - Accuracy on test data : 97.90%
---

## ⚙️ Installation

1. **Clone the repository:**
```bash
git clone [https://github.com/Surajpatel28/Fake_News_Detector.git](https://https://github.com/Surajpatel28/Fake_News_Detector.git)
cd Fake_News_Detector
```

2. **Create & activate virtual environment:**
```bash
python3 -m venv venv
source venv/bin/activate
```

3. **Install dependencies:**
```bash
pip install -r requirements.txt
```

---

## 🚀 Usage
1. **Launch Jupyter Notebook:**
```bash
jupyter notebook
```

2. **Open** `Fake News Prediction.ipynb` and run each cell.
3. **Explore** feature engineering, model training, and evaluation sections.

---

## 🗂️ Project Structure

```text
Fake_News_Detector/
│
├── dataset/              # Raw and processed data files
│   └── train.csv
├── Fake News Prediction.ipynb  # Main notebook
├── requirements.txt      # Python dependencies
└── README.md             # Project overview and instructions
```

---

## 🔮 Future Work

- Integrate **LIME** for explainability.
- Deploy as a **Streamlit** web app.
- Extend to **multilingual** fake news detection.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo.
2. Create a feature branch: `git checkout -b feature/YourFeature`.
3. Commit your changes: `git commit -m 'Add Your Feature'`.
4. Push to branch: `git push origin feature/YourFeature`.
5. Open a Pull Request.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

> Made by Suraj Patel

