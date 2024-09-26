# Retrieval-Augmented Generation (RAG) Notebook

This notebook demonstrates the use of Retrieval-Augmented Generation (RAG) techniques using various libraries and APIs such as HuggingFace, LangChain, Pinecone, and OpenAI. The goal is to process a dataset of resumes, embed the text data, store it in a vector database, and perform queries to retrieve relevant information.

## Skills and Resources

**Skills:**
- HuggingFace
- LangChain
- Pinecone
- OpenAi

**Other Resources:**
- [Get your Groq API Key](https://console.groq.com/keys)
- [Get your Pinecone API Key](https://www.pinecone.io/)
- [Get your OpenAI API Key](https://www.openai.com/)

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine.

2. Set up a virtual environment:
   ```
   python -m venv .env
   source .env/bin/activate  # On Windows, use `.env\Scripts\activate`
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Set up your environment variables:
   Create a `.env` file in the root directory and add your API keys:
   ```
   GROQ_API_KEY=your_groq_api_key
   OPENAI_API_KEY=your_openai_api_key
   PINECONE_API_KEY=your_pinecone_api_key
   ```

5. Make sure you have the necessary permissions and access to the APIs mentioned in the `.env` file.


Project Structure
`.env`: Contains environment variables and API keys (not tracked by git)
`.gitignore`: Specifies files and directories that should not be tracked by git
`requirements.txt`: Lists all Python dependencies for the project