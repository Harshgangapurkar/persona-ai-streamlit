# Persona AI — Streamlit Edition 🤖

🚀 **Live Demo:** [Launch Persona AI](https://persona-ai-app-harsh.streamlit.app)

Persona AI is an interactive AI assistant built with Streamlit that lets users interact with different AI personalities for personalized conversations, learning, and problem-solving. Choose a persona, enter your prompt, and experience AI responses tailored to different communication styles.

## ✨ Features

- **Multiple AI Personas:** Switch between different personalities, including Teacher and other conversational styles.
- **Groq API Integration:** Generate AI responses using Groq-powered language models.
- **Interactive Chat Interface:** Enjoy a simple, user-friendly conversational experience built with Streamlit.
- **Personalized Responses:** Experience different tones, explanations, and communication styles based on your selected persona.
- **Live Deployment:** Access the application directly through your browser without installing it locally.

## 🌐 Try It Live

**[👉 Open Persona AI](https://persona-ai-app-harsh.streamlit.app)**

### 🔑 Important: Groq API Key Required

The Groq API integration is currently working. To use the application, **please enter your own valid Groq API key** when prompted.

1. Visit the [Groq Console](https://console.groq.com/keys).
2. Sign in and create an API key.
3. Open the live Persona AI application.
4. Enter your API key in the designated field.
5. Select your preferred AI personality and start chatting!

**Security note:** Never share your API key publicly, commit it to GitHub, or include it in screenshots. Use only the designated input field, and avoid using an API key you cannot afford to have exposed.

## 🛠️ Tech Stack

- **Python** — Application logic
- **Streamlit** — Interactive web interface
- **Groq API** — AI-powered text generation
- **Git & GitHub** — Version control and source code management
- **Streamlit Community Cloud** — Web deployment

## 💻 Run Locally

### 1. Clone the repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd <YOUR_PROJECT_FOLDER>
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Start the application

```bash
streamlit run app.py
```

Open the local URL displayed in your terminal and provide your Groq API key when prompted.

*Note: Replace `app.py` with your actual Streamlit entry-point filename if it differs.*

## 🔐 API Key & Privacy

- Users should provide their own Groq API key to access AI functionality.
- Keep API keys private and never commit secrets to version control.
- Do not assume that API keys entered into a third-party application are secure unless its implementation and data handling have been verified.
- API availability, model access, and usage limits depend on Groq and the user's account.

## 🎯 Project Objective

The goal of Persona AI is to explore how large language models can deliver more personalized and engaging interactions through configurable AI personalities and a lightweight web interface.

## 👨‍💻 Author

**Harsh Vivek Gangapurkar**

AI & Data Science Student | AI/ML Enthusiast | Aspiring AI Engineer

---

⭐ If you find this project interesting, consider starring the repository on GitHub and sharing your feedback!

**Try it now:** [Persona AI — Live Application](https://persona-ai-app-harsh.streamlit.app)

