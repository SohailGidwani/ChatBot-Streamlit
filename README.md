

# Internal Support Chatbot

## Overview
This project implements an AI-powered chatbot designed for internal support within IIFL. It leverages advanced language models for understanding and responding to employee queries. The chatbot integrates semantic search capabilities using Pinecone and sentence transformers, and refines user queries for improved response accuracy.

## Features
- **AI-Powered Responses**: Utilizes GPT-3.5 for generating accurate and relevant responses.
- **Semantic Search**: Integrates Pinecone indexing for retrieving information from a knowledge base.
- **Query Refinement**: Enhances user queries for better understanding using OpenAI's `text-davinci-003` model.
- **Streamlit Web Interface**: Provides an interactive web interface for users to interact with the chatbot.

## Installation

To set up the project, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/SohailGidwani/ChatBot-Streamlit.git
   cd your-repo-name
   ```

2. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the chatbot application:

```bash
streamlit run main.py
```

Navigate to the displayed URL to interact with the chatbot via the web interface.

## Configuration

1. **OpenAI API Key**: Set up your OpenAI API key in the `utils.py` file.

2. **Pinecone API Key**: Update the Pinecone API key in `utils.py` for the vector database.

## Files Description

- `main.py`: Main application script using Streamlit for the web interface.
- `utils.py`: Utility functions for query refinement, conversation string construction, and Pinecone index querying.
- `requirements.txt`: List of Python dependencies for the project.


