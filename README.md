# FAQ Bot

An AI-powered FAQ chatbot built with vanilla HTML, CSS, and JavaScript. No backend, no build step, no dependencies — just open `index.html` in a browser.

## Features

- **Preprocessing**: lowercases input, strips punctuation, removes stopwords
- **TF-IDF + cosine similarity**: matches user questions to the closest FAQ entry
- **Intent layer**: catches greetings/thanks/goodbyes before falling back to similarity matching
- **Confidence-tiered responses**: high-confidence direct answer, medium-confidence hedge, low-confidence fallback to contact support
- **Interactive chat UI**: typing indicator, suggestion chips, smooth scrolling, confidence score shown per reply

## Usage

Just open `index.html` in any modern browser — no installation required.

To customize the knowledge base, edit the `FAQ` array near the top of the `<script>` block in `index.html`.

## Tech

Pure HTML/CSS/JS. TF-IDF and cosine similarity are implemented from scratch (~40 lines) for transparency and zero dependencies.
