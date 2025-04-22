# 🧠 NLP Learning Journey with Semantic Search Practice

Welcome to **NLP Learning Journey** — a hands-on, project-based self-study track designed to help you go from beginner to intermediate level in Natural Language Processing (NLP) using Python.

This repository contains all learning scripts, notes, and mini-projects created while studying NLP fundamentals — from text cleaning and vectorization, all the way to sentence embeddings and semantic search.

---

## 📚 What You'll Find Here

| Week | Topics Covered                                        | Highlights                                |
|------|--------------------------------------------------------|-------------------------------------------|
| 1    | NLP Basics: Tokenization, POS, Lemmatization           | spaCy-based verb counter, tagger pipeline |
| 2    | Text Vectors: BoW, TF-IDF, Word2Vec                    | Word vector exploration, TF-IDF scoring   |
| 3    | Sentence Embeddings & Similarity                       | SBERT, cosine similarity, clustering      |
| 4    | Final Project: Semantic Search Engine (NLP-powered)    | Input ranking using sentence transformers |


---

## 🛠 Tools Used

- Python 3.12+
- spaCy (`en_core_web_md` or `lg`)
- NLTK
- scikit-learn
- sentence-transformers (`all-MiniLM-L6-v2`)
- matplotlib / wordcloud (for visualizations)

---

## 📁 Folder Structure

```
NLP_Learning_Track/
├── day01_to_day14/               # Step-by-step exercises and notebooks
├── semantic_search_project/     # Day 14 final project: semantic search
├── utils/                       # Reusable NLP utilities
├── notes/                       # Markdown notes from each day
├── README.md
└── requirements.txt
```

---

## 🚀 How to Get Started

1. Clone this repo:
```bash
git clone https://github.com/your-username/NLP_Learning_Track.git
```

2. Set up your environment:
```bash
cd NLP_Learning_Track
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

3. Explore by topic or day:
```bash
cd day01_to_day14/
python day09_tfidf_vectorization.py
```

4. Run the final project:
```bash
cd semantic_search_project/
python app.py
```

---

## 🧠 Project Highlights
- Real-world NLP pipeline examples
- SBERT-powered semantic matching
- Visual insights with word clouds and entity timelines
- Designed for hands-on learners

---

## 🤝 Contributions
This repository was created as part of Jason Lin’s personal NLP learning journey, powered by daily interaction with ChatGPT.

Contributions, suggestions, or learning ideas are always welcome via pull request or issues.

---

## 📜 License
MIT License
