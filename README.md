OLLAMA Web Scraper Summarization RAG Solution

Requirements:
argparse
langchain
langchain-community
gpt4all
chromadb

** First : You will need to first run Ollama and serve a LLM
ollama run (llm) code example uses llama2 you can change to any ollama model you wish.

** Then you will need to run the rag.py file with the following structure:

python rag.py --url https://examplewebsite.com

Depending on your system and GPU performance this could take seconds or minutes.

Work in progress.
