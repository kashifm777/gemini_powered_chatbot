# Gemini Powered Chatbot
## Streamlit Web App

This Streamlit web app provides a user-friendly interface to interact with Google's powerful Gemini Pro generative AI model. Ask questions and receive informative responses in a chat-like environment.

### 1. Key Features:

- Seamless interaction with Gemini Pro through Google's GenerativeAI library.
- Streamlit-based interface for a smooth user experience.
- Ask open-ended questions and receive comprehensive answers.

### 2. Requirements:

- Python 3.x
- Streamlit (`pip install streamlit`)
- `dotenv` library (`pip install python-dotenv`)
- Google Cloud Project with GenerativeAI API enabled ([Generative AI](https://cloud.google.com/ai/generative-ai))

### 3. Setup:

1. Create a virtual environment (recommended): `python -m venv venv`
2. Activate the environment: `source venv/bin/activate` (Windows: `venv\Scripts\activate`)
3. Install dependencies: `pip install streamlit python-dotenv`
4. Create a `.env` file in the project directory:
   - Add `GOOGLE_API_KEY=<YOUR_API_KEY>` (replace with your GenerativeAI API key)

### 4. Running the App:

1. Open a terminal in the project directory.
2. Run the app: `streamlit run app.py`
3. Access the app in your web browser at http://localhost:8501.

### 5. Usage:

1. Type your question or prompt in the "Ask a question:" text input field.
2. Click the "Ask" button.
3. The app will display the Gemini Pro response, potentially broken down into separate sentences for better readability.

### 6. Additional Notes:

- Experiment with different types of questions to explore Gemini Pro's capabilities.
- Be mindful of API usage limits and potential costs when employing cloud services.
- Consider implementing error handling for a more robust user experience.
- Explore advanced Streamlit features for customization (like sidebars or multimedia).

### 7. Disclaimer:

The quality and accuracy of Gemini Pro's responses may vary depending on the complexity of the question and the model's training data. It's recommended to use this application for informational purposes only and consult a qualified professional for specific needs.