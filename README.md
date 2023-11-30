# Chat with Documents Application

## Introduction

"Chat with Documents" is an LLM application built using OpenAI, ChromaDB, Langchain, and Streamlit framework. It leverages the power of Generative AI to provide a chat interface for querying and interacting with a variety of documents in pdf, docx and txt extensions.

## Features

- **AI-Powered Chat Interface**: Utilizes OpenAI's language models for natural language understanding and generation.
- **Document Management**: Leverages ChromaDB for efficient storage and retrieval of vector data.
- **Advanced Language Processing**: Integrates Langchain for complex language processing tasks.
- **Interactive Web Interface**: Built with Streamlit for an easy-to-use and interactive user experience.

## Setup

1. **Clone the Repository**: 
```
git clone https://github.com/sowole-aims/chat-with-documents-app.git
```

``` 
cd chat-with-documents-app
```
2. **Install Dependencies**: Run 

```
pip install -r requirements.txt
```
in the project directory.

3. **Environment Setup**: Set up environment variable for OpenAI in `.env` file.

## Usage

1. **Start the Application**: Run 

```
streamlit run chat_with_documents.py
```
Open your browser and visit `http://localhost:8501` to access the application.

2. **Interact with the Chat**: Enter your queries related to the documents in the chat interface.





## License
This project is licensed under the [MIT License](LICENSE).


## Acknowledgments
This project utilizes the Langchain library, OpenAI API, and Streamlit Web Framework.

## Important Note
Please ensure that you have a valid OpenAI API key to use the application. If you don't have one, sign up for an API key at the OpenAI website before running the chatbot.


