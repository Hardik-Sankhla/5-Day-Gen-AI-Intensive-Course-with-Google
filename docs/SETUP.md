# Setup Instructions

Follow these steps to set up a local development environment for this repository.

1. Clone the repository:

```powershell
git clone https://github.com/Hardik-Sankhla/5-Day-Gen-AI-Intensive-Course-with-Google.git
cd 5-Day-Gen-AI-Intensive-Course-with-Google
```

2. Create and activate a virtual environment (Windows example):

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

3. Install Python dependencies:

```powershell
pip install --upgrade pip
pip install -r requirements.txt
```

4. Jupyter notebooks:

```powershell
jupyter notebook
```

5. Accounts and external setup (course-specific):
- Create a Kaggle account and phone-verify for codelabs.
- Create an AI Studio (Vertex AI) account and generate API keys if using Live/Vertex features.

Notes:
- If you prefer `poetry` or `pipx`, you can adapt the environment steps accordingly.
- The `requirements.txt` is intentionally minimal; add packages to it as needed for specific codelabs.
