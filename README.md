# AI Fact-Checking Web App

## Overview

This project is an AI-powered Fact-Checking Web Application that automatically verifies factual claims from uploaded PDF documents.

The system extracts claims such as:
- statistics
- percentages
- dates
- measurable statements
- company metrics

It then cross-references those claims with live web data and classifies them as:
- Verified
- Inaccurate
- False

---

## Features

- PDF Upload Interface
- AI-based Claim Extraction
- Live Web Verification
- Fact Classification
- Streamlit UI
- Public Cloud Deployment

---

## Tech Stack

- Python
- Streamlit
- Groq (Llama 3)
- Tavily Search API
- pypdf

---

## Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py