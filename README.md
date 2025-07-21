# 🧠 Simple Chatbot using NLTK and Python

This project demonstrates how to build a **rule-based chatbot** using Python and the **Natural Language Toolkit (NLTK)**. It’s a beginner-friendly tutorial project to understand basic NLP concepts and create a conversational bot that can handle simple queries.

---

## 🚀 Features

- Tokenization & Lemmatization using **NLTK**
- Basic conversational flow using **pattern matching**
- Text preprocessing for better understanding
- Response generation using **TF-IDF** and **cosine similarity**
- Runs locally with a simple terminal interface


---

## 📖 How It Works

1. The bot loads a custom text file (`corpus.txt`) as its knowledge base.
2. User input is cleaned and processed using NLTK (tokenization, lemmatization).
3. TF-IDF vectorization is applied to compare user input with existing knowledge.
4. A relevant response is returned based on cosine similarity.

---

## 🔧 Installation

```bash
git clone https://github.com/your-username/chatbot-nltk
cd chatbot-nltk
pip install -r requirements.txt
```

---

## 🧪 Usage

```bash
python chatbot.py
```

Type your query in the terminal and the chatbot will try to respond appropriately. Type `bye` to exit.

---

## 📚 Dependencies

- Python 3.x
- NLTK
- Scikit-learn
- NumPy

Install all with:

```bash
pip install -r requirements.txt
```

---

## 📝 License

This project is open-sourced under the MIT License.
