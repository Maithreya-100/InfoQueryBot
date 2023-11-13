# InfoQueryBot

InfoQueryBot is a Python project that leverages the power of natural language processing and information retrieval to answer questions based on a pre-loaded dataset of documents. The project uses the OpenAI language model and the langchain library to create a question-answering bot.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Setup](#setup)
- [Dependencies](#dependencies)
- [License](#license)

## Introduction

InfoQueryBot is designed to answer questions by retrieving relevant information from a pre-loaded dataset. The project utilizes the langchain library, which provides a framework for chaining various natural language processing components together.

The main components of InfoQueryBot include:
- **OpenAI Language Model:** The project uses the OpenAI language model for natural language understanding and generation.
- **langchain Library:** InfoQueryBot leverages the langchain library to create a processing chain that includes document loading, text splitting, embedding, and vector indexing.
- **FAISS Vector Index:** The project utilizes the FAISS library for efficient similarity search and vector indexing.

## Features

- **Question Answering:** InfoQueryBot can answer questions based on the information available in the pre-loaded dataset.
- **Efficient Vector Indexing:** FAISS is used to create an efficient vector index for quick information retrieval.

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/InfoQueryBot.git

2. Install the required dependencies:

   ```bash 
   pip install -r requirements.txt

3. Set up the OpenAI API key:

    Replace the placeholder in the code with your OpenAI API key:

    os.environ["OPENAI_API_KEY"] = "your-openai-api-key"

4. Run the script to pre-load the dataset and create the vector index:

   ```python
      python setup.py

## Dependencies

- langchain
- OpenAI
- FAISS

  Other dependencies are listed in the *requirements.txt* file.

## License
  This project is licensed under the MIT License - see the LICENSE file for details.

  ```kotlin
    Feel free to use this markdown file as needed!
