# 🪨 ChatGeology: Geology-Aware LLM Pipeline

This project provides an end-to-end workflow for extracting, cleaning, and leveraging geological PDF reports to fine-tune Large Language Models (LLMs), and then deploys them as interactive APIs. It also includes an API-based approach to interact with LLaMA models for document Q&A and summarization.

---

## 🚀 Features

- **PDF Extraction & Cleaning:** Automatic extraction and cleaning of text from geological PDF reports.
- **LLM Training Data Preparation:** Converts cleaned text into structured training data for LLMs.
- **Efficient Fine-Tuning:** Fine-tunes LLMs (with LoRA for efficiency) on your custom geological data.
- **API Deployment:** Deploys the trained model as a FastAPI service for real-time Q&A.
- **LLaMA API Integration:** Includes a notebook for querying and summarizing PDFs using LLaMA via API.

---


## 📝 Notebooks Overview

- **chatGeology.ipynb**
  - End-to-end pipeline: PDF extraction, cleaning, data preparation, LLM fine-tuning, and API deployment.
- **llama-api.ipynb**
  - Lightweight API-based pipeline for extracting, summarizing, and querying PDFs using LLaMA models.

---
