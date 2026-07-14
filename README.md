# FAQ Chatbot — NLP (Web Version)

A self-contained FAQ chatbot built with vanilla HTML/CSS/JS. No backend, no
dependencies — everything (NLP preprocessing, TF-IDF vectorization, and
cosine similarity matching) runs client-side in the browser.

## How it works
1. **Preprocessing** — lowercases input, strips punctuation, tokenizes, and
   removes stopwords.
2. **Vectorization** — builds a TF-IDF vector for every FAQ question and for
   the user's query, implemented from scratch in JavaScript.
3. **Matching** — computes cosine similarity between the query vector and
   every FAQ vector, returning the closest match (with a confidence score)
   if it clears a similarity threshold.

## Run it
Just open `index.html` in any browser — no build step required.

**Live demo:**[ https://mayar846.github.io/language-translator-web-/](https://mayar846.github.io/literate-garbanzo/)

## Deploy for free
Push this folder to a GitHub repo and enable **GitHub Pages** (Settings →
Pages → Branch: main) to get a public link instantly.

## Customize
Edit the `FAQ` array at the top of the `<script>` in `index.html` to swap in
your own questions and answers — the NLP pipeline works with any dataset.

## Tools
HTML · CSS · JavaScript (TF-IDF + cosine similarity implemented from scratch)
