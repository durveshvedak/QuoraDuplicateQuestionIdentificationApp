# 🔍 QuoraDuplicateQuestionIdentificationApp

> Identifying semantically duplicate Quora question pairs using NLP and machine learning — built in Java with a full pipeline from feature extraction to classification.

![Java](https://img.shields.io/badge/Java-8+-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-semantic_similarity-blueviolet?style=flat-square)
![Quora](https://img.shields.io/badge/Quora-dataset-B92B27?style=flat-square)

---

## 📖 Overview

This project tackles the **Quora Question Pairs** challenge: given two questions, determine whether they are semantically equivalent. This is a classic NLP problem with real-world applications in deduplication, search, and knowledge base management. The solution is implemented in Java and covers the full ML pipeline from text preprocessing to classification.

## 🧠 How It Works

```
[Quora Question Pairs Dataset]
          │
          ▼
[Text Preprocessing]
  - Tokenization
  - Stop word removal
  - Stemming/Lemmatization
          │
          ▼
[Feature Engineering]
  - TF-IDF similarity
  - Jaccard similarity
  - Edit distance
  - Common word ratio
          │
          ▼
[ML Classifier]
  - Binary classification (duplicate / not duplicate)
          │
          ▼
[Prediction Output]
```

## ✨ Features

- **Java NLP pipeline** — End-to-end question pair processing in Java
- **Multiple similarity metrics** — Lexical and semantic similarity features
- **Quora dataset** — Trained and evaluated on the official Quora question pairs dataset
- **Binary classification** — Predicts duplicate vs. non-duplicate pairs
- **Modular architecture** — Clean separation of preprocessing, features, and classification

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Language | Java 8+ |
| NLP | Custom Java NLP pipeline |
| ML | Java ML classifiers |
| Dataset | Quora Question Pairs |

## 🚀 Quick Start

```bash
# Navigate to the project directory
cd QuoraDuplicateQuestionIdentification/

# Compile with Maven or your preferred Java build tool
mvn clean install

# Run the application
java -jar target/QuoraDuplicateQuestionIdentification.jar
```

## 📂 Repo Structure

```
└── QuoraDuplicateQuestionIdentification/
    ├── src/          # Java source files
    ├── data/         # Question pair datasets
    └── pom.xml       # Maven build config
```

## 💡 Applications

- **Forum deduplication** — Automatically merge duplicate questions
- **Search optimization** — Surface the best existing answer for new questions
- **Knowledge base management** — Keep Q&A databases clean and consolidated
- **Chatbot improvement** — Recognize paraphrased user intents

---

<p align="center">Made with ❤️ by <a href="https://github.com/durveshvedak">Durvesh Vedak</a></p>
