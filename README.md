# MacroSnap 🥗

MacroSnap is a simple AI nutrition chatbot that helps users understand what they are eating. You can either type your meal details or upload a photo, and the app uses Gemini to estimate the calories and macros.

It also sends the final meal summary to WhatsApp using Twilio.

## Features

- Analyze food from a text description
- Analyze food from a meal photo
- Estimate calories, protein, carbs, and fat
- Chat with Gemini about meals and nutrition
- Send the nutrition summary to WhatsApp

## Tech Stack

- Python
- Streamlit
- Google Gemini
- Twilio WhatsApp

## Run Locally

1. Clone the repository.

```bash
git clone https://github.com/GurudevMB/AI-CHAT-VISION-BOT.git
cd AI-CHAT-VISION-BOT
```

2. Install the required packages.

```bash
pip install -r requirements.txt
```

3. Create `.streamlit/secrets.toml` and add your Gemini and Twilio credentials.

Use `.streamlit/secrets.toml.example` as a reference.

4. Start the app.

```bash
streamlit run app.py
```

The app will open in your browser at `http://localhost:8501`.

## Live Demo

https://ai-chat-vision-bot-ah9mpduxveioz6kwwauh3j.streamlit.app/