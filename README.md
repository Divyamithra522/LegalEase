# LegalEase – AI-Powered Legal Document Generator

Student project using Generative AI to create structured legal-document drafts.

## Features
- Employment Contract, NDA, Lease Agreement, Freelance Contract and General Agreement
- Streamlit frontend
- FastAPI backend
- Gemini AI integration
- Editable preview
- TXT, DOCX and PDF export

## Setup
1. Install Python 3.10+
2. `python -m venv venv`
3. Activate the virtual environment
4. `pip install -r requirements.txt`
5. Copy `.env.example` to `.env`
6. Add your Gemini API key

## Run
Backend: `uvicorn backend.main:app --reload`

Frontend: `streamlit run frontend/app.py`

Generated legal text is an AI-assisted draft and should be reviewed before real-world use.
