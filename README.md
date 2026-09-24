# COGNI_CLAN

## Smart India Hackathon 2026 — Prototype

### Problem Statement

**AI-Based Cognitive Gaming and Memory Assistance Platform for Elderly Dementia Patients in North Eastern Region (NER)**

**Problem Statement ID:** [Add PS Number]

**Team Name:** COGNI_CLAN

---

## Project Overview

COGNI_CLAN is a prototype developed for **Smart India Hackathon (SIH) 2026** based on the above problem statement.

The project demonstrates an AI-assisted cognitive gaming and memory assistance platform designed around the requirements described in the SIH problem statement.

This repository contains the source code of our working prototype, including the frontend, backend, AI/ML components, synthetic training data, authentication, database integration, and testing components.

---

## Prototype

The prototype consists of a web-based frontend connected to a Python FastAPI backend and AI/ML components.

The repository provides the source code required to understand, configure, and run the prototype locally.

---

## Technology Stack

### Frontend

- HTML5
- CSS3
- JavaScript

### Backend

- Python
- FastAPI
- SQLAlchemy
- PostgreSQL

### AI / Machine Learning

- Python
- NumPy
- SciPy
- Scikit-learn
- PyTorch
- Transformers

### Development & Testing

- Git
- GitHub
- Python virtual environment
- Pytest

---

## Project Structure

```text
COGNI_CLAN/
│
├── ai/
│   ├── data/
│   ├── explainability/
│   ├── inference/
│   ├── models/
│   ├── preprocessing/
│   └── training/
│
├── backend/
│   ├── app/
│   │   ├── ai/
│   │   ├── routes/
│   │   ├── auth.py
│   │   ├── config.py
│   │   ├── database.py
│   │   ├── main.py
│   │   ├── models.py
│   │   ├── schemas.py
│   │   └── security.py
│   │
│   ├── auth.py
│   ├── requirements.txt
│   └── .env.example
│
├── data/
│   └── synthetic/
│       └── training_data.csv
│
├── frontend/
│   ├── css/
│   ├── js/
│   ├── locales/
│   └── HTML pages
│
├── tests/
│
├── .env.example
├── .gitignore
├── README.md
└── requirements.txt