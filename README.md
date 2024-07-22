# QA Chatbot

Welcome to the QA Chatbot project, an advanced question-answering system leveraging the Gemini API to deliver precise and contextually relevant responses. This chatbot utilizes the Generative Model from Google’s Gemini API and is built with Streamlit for an interactive and efficient user experience..

## Key Features

- **Google Gemini API**
    - The chatbot uses Google’s Gemini API for natural language processing and generating human-like responses. This API enhances the chatbot's ability to understand and respond to a wide range of queries.
- **Streamlit**
    - Streamlit is used to create a seamless web interface for the chatbot. It allows for real-time interactions and displays the chat history, providing an intuitive and user-friendly experience.
- **Session State Management**
    - The chatbot maintains a session state to keep track of the chat history, ensuring continuity in the conversation.

## Installation Process

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/qa-chatbot.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd qa-chatbot
    ```

3. **Set up the environment:**
    - Ensure you have Python installed. Create a virtual environment and activate it:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

4. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

5. **Set up environment variables:**
    - Create a `.env` file in the project directory and add your Gemini API key:
    ```
    GOOGLE_API_KEY=your_google_api_key
    ```

6. **Run the application:**
    ```bash
    streamlit run qachat.py
    ```

## Usage

1. **Access the Chatbot:**
    - Open your browser and navigate to the URL provided by Streamlit to interact with the chatbot locally.

2. **Ask Questions:**
    - Type your questions in the input field and press the "Ask the question" button. The chatbot will generate and display responses using the Gemini API.

3. **View Chat History:**
    - The chat history is displayed on the same page, showing the interaction flow between the user and the chatbot.

## Customization and Development

- **Modify the Code:**
    - The codebase is straightforward to customize. You can adjust the response handling, UI elements, or integrate additional features as needed.

- **Extend Functionality:**
    - Enhance the chatbot’s capabilities by integrating other APIs, adding more sophisticated NLP models, or improving the session management.

## Credits

- **Developer:** Arnav Jain
- **Technologies Used:** Google Gemini API, Streamlit, Python
- **Website:** Visit my personal website at [arnavj.me](https://arnavj.me)
