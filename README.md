# CTSE Lecture Notes Chatbot

## Overview
This project is a chatbot built using LangChain and OpenAI's GPT-4 model. The chatbot answers questions based on CTSE lecture notes provided in PDF format.

## Features
- Loads and processes lecture notes from PDF files.
- Uses OpenAI's GPT-4 for natural language understanding and response generation.
- Provides accurate answers to questions about the lecture notes.

## Folder Structure


GitHub Copilot
.gitignore File
Here’s a .gitignore file to exclude unnecessary files and sensitive information from your Git repository:

README.md File
Here’s a README.md file for your project:

# CTSE Lecture Notes Chatbot

## Overview
This project is a chatbot built using LangChain and OpenAI's GPT-4 model. The chatbot answers questions based on CTSE lecture notes provided in PDF format.

## Features
- Loads and processes lecture notes from PDF files.
- Uses OpenAI's GPT-4 for natural language understanding and response generation.
- Provides accurate answers to questions about the lecture notes.

## Folder Structure

ctse-chatbot/ 
├── data/ # Folder for storing lecture notes in PDF format 
├── notebooks/ # Jupyter Notebook for the chatbot 
│ 
|   └── chatbot-ctse.ipynb 
├── requirements.txt # List of dependencies 
├── .env # Environment variables (e.g., OpenAI API key) 
├── README.md # Project documentation 
└── .gitignore # Git ignore file


## Prerequisites
- Python 3.9 or later
- OpenAI API key

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd ctse-chatbot

2. Create a virtual environment and activate it:

    ```bash
    python -m venv .venv
    source .venv/bin/activate  # On Mac/Linux
    .venv\Scripts\activate     # On Windows

3. Install dependencies:

    ```bash
    pip install -r requirements.txt

4. Add your OpenAI API key to a .env file:

    ```bash
    OPENAI_API_KEY=your_openai_api_key

5. Place your lecture notes (PDF files) in the data/ folder.

6. Run the Jupyter Notebook:

    ```bash
    jupyter notebook

Open chatbot-ctse.ipynb and run all cells.

## Usage

- Ask questions about the lecture notes in the chatbot interface.
- Type exit to stop the chatbot.

## Dependencies
- langchain
- langchain-openai
- openai
- chromadb
- tiktoken
- python-dotenv
- pypdf
- notebook
