# TextMind AI

AI-powered text summarization platform built using FastAPI, PyTorch, and Hugging Face Transformers.

TextMind AI leverages the T5 Transformer architecture to generate concise and meaningful summaries from long-form text through an intuitive web interface.

---

## Features

* Abstractive Text Summarization
* FastAPI Backend
* Interactive Web Interface
* Hugging Face Transformers Integration
* T5 Transformer Architecture
* Cross-Platform Support (CPU, CUDA, Apple Silicon)
* Real-Time Summary Generation

---

## Tech Stack

* Python
* FastAPI
* Hugging Face Transformers
* PyTorch
* HTML
* CSS
* JavaScript

---

## Project Structure

```text
TextMind-AI/
│
├── app.py
├── index.html
├── requirements.txt
├── README.md
├── model-training.ipynb
├── Home.png
└── Summarized.png
```

---

## Project Architecture

```text
User Input
     ↓
FastAPI Backend
     ↓
T5 Transformer Model
     ↓
Generated Summary
```

---

## How It Works

1. User enters text in the web interface.
2. FastAPI receives the request.
3. Input text is cleaned and tokenized.
4. T5 Transformer generates an abstractive summary.
5. Summary is returned through the API and displayed on the frontend.

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/SiddhanthSingh14/TextMind-AI.git
cd TextMind-AI
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Model Setup

The trained model files are not included in this repository due to GitHub file size limitations.

You can download and use a pretrained T5 model directly from Hugging Face:

```python
from transformers import T5ForConditionalGeneration, T5Tokenizer

model = T5ForConditionalGeneration.from_pretrained("t5-small")
tokenizer = T5Tokenizer.from_pretrained("t5-small")
```

Alternatively, place your trained model files inside:

```text
saved_summary_model/
```

---

## Running the Application

Start the FastAPI server:

```bash
uvicorn app:app --reload
```

Open your browser:

```text
http://127.0.0.1:8000
```

---

## Dataset

This project was trained using the SAMSum Dataset, a dialogue summarization dataset specifically designed for conversational text summarization tasks.

---

## Screenshots

### Home Page

![Home Page](Home.png)

### Generated Summary

![Generated Summary](Summarized.png)

---

## Future Improvements

* PDF Summarization
* DOCX File Support
* Multiple Transformer Models
* ROUGE Score Evaluation
* Hugging Face Spaces Deployment
* User Authentication
* Summary History Storage

---

## Author

### Siddhanth Singh

B.Tech Computer Science & Engineering

Interests:

* Artificial Intelligence & Machine Learning
* Natural Language Processing
* Competitive Programming
* Backend Development

GitHub: https://github.com/SiddhanthSingh14

```
```
