# LangChain Summarization App

This repository contains a Streamlit application that summarizes text from YouTube videos or websites using the LangChain library and Hugging Face models.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/langchain-summarization-app.git
    cd langchain-summarization-app
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Create a `.env` file in the root directory and add your Hugging Face token:
    ```properties
    LANGCHAIN_TRACING_V2 = 
    LANGCHAIN_ENDPOINT = 
    LANGCHAIN_API_KEY = 
    LANGCHAIN_PROJECT = 
    HF_TOKEN = 
    ```

## Usage

1. Run the Streamlit application:
    ```sh
    streamlit run app.py
    ```

2. Open your web browser and go to `http://localhost:8501`.

3. Enter your Hugging Face API token and the URL of the YouTube video or website you want to summarize.

4. Click the "Summarize the Content from YT or Website" button to get the summary.

## Project Structure

- **a.py**: Contains a script to call the Hugging Face Inference API.
- **app.py**: The main Streamlit application for summarizing text from YouTube videos or websites.
- **experiments.ipynb**: Jupyter notebook for experimenting with Hugging Face models and LangChain.
- **.env**: Environment file to store sensitive information like API tokens.
- **requirements.txt**: List of dependencies required for the project.

