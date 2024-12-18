# RagChatbot
This chatbot interfaces with a LangChain agent designed to answer questions about fake hospital data.
The agent uses RAG over both structured and unstructured data that has been synthetically generated.

## Preliminaries
- Create OpenAI API account
- Create LangChain API account
- Open Neo4j Aura Instance
- Create .env file similar to the `example_.env_file` and add the necessary missing values.

## Running the up
- Clone the repositry
- Run `docker-compose up --build`
- Access the UI at http://localhost:8501/ and begin chatting with your chatbot
