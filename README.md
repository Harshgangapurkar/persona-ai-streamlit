# Persona AI — Streamlit Edition (matched to original project)

This is a Streamlit port of the uploaded `persona-ai-complete` project. It preserves the original provider configuration, eight preset personas, custom persona flow, persona system prompts, safety suffix, key entry, three-step workspace flow, and multi-turn chat.

## Run on Windows
Open a terminal in this folder:

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
streamlit run app.py
```

Open `http://localhost:8501`.

If PowerShell blocks activation, use Command Prompt:
```bat
.venv\Scripts\activate.bat
python -m pip install -r requirements.txt
streamlit run app.py
```

## Deploy
1. Push this folder to a GitHub repository.
2. Sign in at https://share.streamlit.io.
3. Create app, select the repository/branch, and set main file path to `app.py`.
4. Deploy.

## Important
No free host guarantees permanent uptime or that a deployment will never be removed. Keep the code in GitHub and a local backup. The app uses the original project's OpenAI-compatible provider interface; compatibility varies, and Anthropic's endpoint in the original project may require a native Anthropic SDK adapter. API providers may charge for usage. Never commit API keys.
