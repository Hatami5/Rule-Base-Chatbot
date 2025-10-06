
---

# 🩺 Medical Chatbot with Flask & NLP

A simple **medical chatbot** built with **Flask** and **Natural Language Processing (NLP)**.
It uses **TF-IDF vectorization** and **cosine similarity** to answer user queries based on a medical research dataset, with a clean **chat-style HTML frontend**.

---

## 🚀 Features

* Friendly web-based chatbot UI (HTML/CSS/JS).
* Text preprocessing (tokenization, stopword removal, lemmatization).
* Smart response generation using **TF-IDF** and **cosine similarity**.
* Handles greetings with predefined messages.
* Fallback responses when no relevant match is found.
* Powered by **Flask** (backend) + **NLTK** + **scikit-learn**.

---

## 📂 Project Structure

```
medical-chatbot/
│── chatbot.py                   # Main Flask application
│── medical research.txt     # Knowledge base (text dataset)
│── templates/
│    └── index.html          # Frontend UI (chat window)
│── static/                  # (Optional) CSS/JS for UI
│── requirements.txt         # Python dependencies
│── README.md                # Project documentation
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Hatami5/Rule-Base-Chatbot-using-NLP.git
cd Rule-Base-Chatbot-using-NLP
```

### 2. Create a Virtual Environment (recommended)

```bash
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Download NLTK Resources

Inside Python shell:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
```

### 5. Run the Application

```bash
python chatbot.py
```

The chatbot will be available at:
👉 `http://127.0.0.1:5000/`

---

## 🖥️ Usage

1. Open the chatbot in your browser.
2. Type a greeting or ask a medical question (e.g. *"What are the symptoms of diabetes?"*).
3. The bot will reply with the most relevant answer from the dataset.
4. Type `bye` to end the conversation.

---

## 📌 Example Interaction

**User:**

```
Hi
```

**Bot:**

```
Hello! I'm here to assist you with your medical concerns. How can I help today?
```

**User:**

```
What are symptoms of influenza?
```

**Bot:**

```
Common symptoms of influenza include fever, cough, sore throat, and muscle aches.
```

---

## 📦 Requirements

Example `requirements.txt`:

```
flask
nltk
scikit-learn
```

---

## 🔮 Future Improvements

* Improve response accuracy with deep learning models (BERT/GPT).
* Expand dataset with multiple medical resources.
* Add chat history storage.
* Enhance frontend with voice input/output.

---

## 🤝 Contributing

Pull requests are welcome!
For major changes, open an issue first to discuss what you’d like to change.

---

## 📜 License

This project is licensed under the **MIT License** 

---
