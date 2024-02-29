# README

This LLM app is made using gemini-pro as the backend and streamlit for interaction

## Prerequisites (requirements.txt)

streamlit
google-generativeai
python-dotenv
Pillow
langchain
langchain-community
pyPDF2
chromadb
faiss-cpu
langchain_google_genai

## How to use

Clone the repository
```markdown
git clone https://github.com/shouryacoded/Gemini_app.git
```

Creating the virtual environment
```markdown
conda create -p venv python=3.10
```

Install the requirements
```markdown
pip install -r requirements.txt
```

Note: Please create your own Gemini API Key and use in the dotenv(.env) file.

Run the app
```markdown
streamlit run pdfapp.py

