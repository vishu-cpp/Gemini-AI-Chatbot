# Gemini-streamlit-chatbot
This repository is about building a chatbot using Google's Gemini-Pro with streamlit.

## Setup Instructions

1. Clone the repository:
    ```sh
    git clone <repository_url>
    cd gemini-pro-streamlit-chatbot
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

3. Set up the environment variables:
    - Create a `.env` file in the root directory.
    - Add your Google API key to the `.env` file:
        ```
        GOOGLE_API_KEY=<your_api_key>
        ```
    **Note**: For security reasons, avoid committing your API key directly to the repository. Use environment variables or secret management tools.

4. Run the Streamlit app:
    ```sh
    streamlit run main.py
    ```
