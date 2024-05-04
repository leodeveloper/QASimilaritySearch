# Question and Answer Similarity Search Application

This project aims to create a Question and Answer (QA) similarity search application using Python. It leverages various libraries and tools including Jupyter Notebook, Pinecone, Vector Database, LangChain, RetrievalQA, ChatGPT, OpenAIEmbeddings, PineconeVectorStore, PyPDFDirectoryLoader, and RecursiveCharacterTextSplitter.

## Features

- **Question-Answer Similarity Search**: Allows users to input a question and retrieves similar questions or answers from a dataset.
- **Integration with Large Language Models**: Integrates with ChatGPT and other large language models for improved understanding and retrieval.
- **Efficient Vector Database**: Utilizes Pinecone as a vector database for fast and scalable similarity search.
- **Support for Various Data Formats**: Supports PDF documents through PyPDFDirectoryLoader and text processing with RecursiveCharacterTextSplitter.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/your_project.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up Pinecone:
   
   Visit [Pinecone](https://www.pinecone.io/) and follow the instructions to create an account and obtain an API key. Replace `YOUR_API_KEY` in `config.py` with your actual API key.

## Usage

1. Start Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

2. Open `QASimilaritySearch.ipynb` and follow the instructions to run the application.

## Contributors

- John Doe (@john_doe)
- Jane Smith (@jane_smith)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
