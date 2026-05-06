# FactCheck AI

AI-powered fact-checking web application that extracts claims from PDF documents and verifies them using live web search and LLM reasoning.

---

## Features

- Upload PDF documents
- Automatic claim extraction
- AI-powered fact verification
- Live web search integration
- Streamlit-based UI
- JSON report download
- Modern responsive interface

---

## Tech Stack

- Python
- Streamlit
- Groq API
- Tavily Search API
- PyMuPDF
- spaCy
- Requests

---

## Project Structure

```bash
factcheck-ai/
│
├── app.py
├── requirements.txt
├── runtime.txt
├── README.md
├── .gitignore
│
├── services/
│   ├── pdf_parser.py
│   ├── claim_extractor.py
│   ├── verifier.py
│   └── web_search.py
│
└── utils/
    └── prompts.py