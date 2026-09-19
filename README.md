# Quant Sports Analyzer

Streamlit app for MASTER SYSTEM PROMPT V3.

## Local
pip install -r requirements.txt
streamlit run app.py

Create `.streamlit/secrets.toml`:
GEMINI_API_KEY = "YOUR_KEY"

Never commit secrets.toml.

## Deploy
Push to GitHub, deploy `app.py` on Streamlit Community Cloud, and put
GEMINI_API_KEY in the app's Secrets settings.
