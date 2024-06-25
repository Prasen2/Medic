# Medic
Medical Chatbot using Pinecone and LangChain
Certainly! Here's a detailed description suitable for a Git repository README for your project:

---

# Medical Chatbot using Pinecone and LangChain

## Overview

This repository contains the implementation of a medical query chatbot developed using Pinecone for vector storage and LangChain framework for natural language processing tasks. The chatbot allows users to ask medical-related questions and retrieves relevant information from a collection of medical documents stored in Pinecone.

## Features

- **Pinecone Integration**: Utilizes Pinecone for efficient storage and retrieval of document embeddings, enabling fast and accurate similarity searches.
  
- **LangChain Framework**: Implements various components of the LangChain framework including document loading, text splitting, embedding generation using HuggingFace models, and response generation using GPT-2.

- **Query Processing**: Transforms user queries into embeddings using pre-trained models, queries Pinecone to find the most relevant documents, and generates responses based on retrieved information.

- **Interactive Chat Interface**: Provides a user-friendly chat interface where users can input medical questions and receive real-time responses.

- **Security and Data Management**: Securely manages API keys and sensitive data using `dotenv` and ensures data integrity throughout the document processing and querying pipeline.

## Tools and Technologies

- **Python**: Primary programming language.
- **LangChain**: Framework for building language models.
- **Pinecone**: Vector database for efficient similarity searches.
- **HuggingFace**: Provides pre-trained models for text embeddings and language generation.
- **Jupyter Notebooks**: Used for development and testing.

## Project Structure

- `data/`: Contains medical documents used for embedding and querying.
- `notebooks/`: Jupyter notebooks for development and testing purposes.
- `src/`: Source code for the chatbot implementation.
- `requirements.txt`: List of dependencies for easy environment setup.

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/your_username/medical-chatbot.git
   cd medical-chatbot
   ```

2. Set up your Python environment and install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory with the following variables:
     ```
     PINECONE_API_KEY=<your_pinecone_api_key>
     HUGGINGFACE_TOKEN=<your_huggingface_token>
     ```

4. Run the chatbot:
   ```
   python src/main.py
   ```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your proposed changes.

