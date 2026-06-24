# TextMind AI

An AI-powered text summarization platform built using FastAPI and Hugging Face Transformers.

## Features

* Abstractive Text Summarization
* T5 Transformer Model
* FastAPI Backend
* Interactive Web Interface
* CPU / CUDA / Apple Silicon Support
* Real-Time Summary Generation

## Tech Stack

* Python
* FastAPI
* Hugging Face Transformers
* PyTorch
* HTML
* CSS
* JavaScript

## Project Architecture

User Input
↓
FastAPI Backend
↓
T5 Transformer Model
↓
Generated Summary

## Screenshots

### Home Page

![Home](screenshots/home.png)

### Generated Summary

![Summary](screenshots/summary.png)

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/TextMind-AI.git
cd TextMind-AI
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run application

```bash
uvicorn app:app --reload
```

Open browser

```text
http://127.0.0.1:8000
```

## Future Improvements

* PDF Summarization
* Multiple Transformer Models
* Hugging Face Deployment
* ROUGE Evaluation Metrics

## Author

Siddhanth Singh
