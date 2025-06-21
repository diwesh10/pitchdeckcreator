# AutoPitch Pro 🚀

An AI-powered startup pitch generator that turns your one-line idea into a downloadable PowerPoint presentation. Built with Streamlit and Google's Gemini.

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://[YOUR_STREAMLIT_APP_URL_HERE])

## ✨ Features

- **AI-Powered Content:** Generates a 10-slide pitch deck using the Gemini AI model.
- **Instant PowerPoint:** Creates a downloadable `.pptx` file from the generated content.
- **Easy to Use:** Simple interface for quick pitch generation.
- **Shareable & Deployable:** Ready to be deployed on Streamlit Cloud.

## 🚀 Deploy Your Own

You can deploy your own instance of this app to Streamlit Cloud with one click:

[![Deploy to Streamlit](https://streamlit.io/button.svg)](https://streamlit.io/deploy?repository=https://github.com/diwesh10/pitchdeckcreator)

After deploying, remember to add your `GOOGLE_API_KEY` to the Streamlit secrets manager to get it running.

## 🛠️ Local Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/diwesh10/pitchdeckcreator.git
    cd pitchdeckcreator
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Add your API Key:**
    - Create a file at `.streamlit/secrets.toml`.
    - Add your Google API key to it:
      ```toml
      GOOGLE_API_KEY = "YOUR_API_KEY_HERE"
      ```

4.  **Run the app:**
    ```bash
    streamlit run app.py
    ``` 