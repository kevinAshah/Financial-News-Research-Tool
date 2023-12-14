
# Financial News Research Tool 

Welcome to the Financial News Analysis Tool, a powerful utility for extracting insights from financial news articles. Whether you're interested in stock market trends or specific companies, this tool allows you to leverage cutting-edge technologies for efficient information retrieval.

![](image.png)

## Key Features

- URL Input: Load URLs or upload text files containing URLs to retrieve article content.
- LangChain Integration: Process article content through LangChain's UnstructuredURL Loader for enhanced data understanding.
- Embedding Vector Construction: Utilize OpenAI's embeddings to construct embedding vectors.
- FAISS Similarity Search: Leverage FAISS, a robust similarity search library, for swift and effective retrieval of relevant information.
- Chatgpt Interaction: Interact with Chatgpt (LLM) by inputting queries and receiving answers along with source URLs.

## How to Use

- Run the main.py script to open the web app in your browser.
- Input URLs directly on the sidebar or upload a text file containing URLs.
- Click "Process URLs" to initiate data loading and processing.
- Observe the system as it performs text splitting, generates embedding vectors, and efficiently indexes them using FAISS.
- The FAISS index is stored locally in a pickle file (faiss_store_openai.pkl) for future use.
- Ask questions and receive answers based on the analyzed news articles.

## Example URLs for Reference

- https://www.moneycontrol.com/news/business/tata-motors-mahindra-gain-certificates-for-production-linked-payouts-11281691.html
- https://www.moneycontrol.com/news/business/tata-motors-launches-punch-icng-price-starts-at-rs-7-1-lakh-11098751.html
- https://www.moneycontrol.com/news/business/stocks/buy-tata-motors-target-of-rs-743-kr-choksey-11080811.html

## Project Structure

- main.py: The main Streamlit application script.
- requirements.txt: A list of required Python packages for the project.
- faiss_store_openai.pkl: A pickle file to store the FAISS index.
- .env: Configuration file for storing the OpenAI API key.
