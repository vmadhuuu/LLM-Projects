# News Research Tool 📈

## Overview

The News Research Tool is an AI-driven application designed to process and retrieve information from multiple news article URLs. Leveraging Streamlit, Langchain, FAISS, and OpenAI embeddings, this tool provides real-time question-answering capabilities along with source references. It is built to facilitate efficient information retrieval and analysis for research purposes.

## Features

- **Data Extraction**: Load news articles from URLs using `UnstructuredURLLoader`.
- **Text Segmentation**: Split text into manageable chunks with `RecursiveCharacterTextSplitter`.
- **Embeddings Creation**: Generate vector embeddings using `OpenAIEmbeddings`.
- **Efficient Retrieval**: Store and retrieve data using a FAISS index.
- **Interactive Interface**: User-friendly interface built with Streamlit for querying and displaying results.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/news-research-tool.git
   cd news-research-tool
   ```

2. Create a virtual environment and activate it:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Create a `.env` file and add your OpenAI API key:
   ```
   OPENAI_API_KEY=your_openai_api_key
   ```

## Usage

1. Run the Streamlit app:

   ```bash
   streamlit run main.py
   ```

2. Enter up to three news article URLs in the sidebar.

3. Click on the "Process URLs" button to start the data extraction and processing pipeline.

4. Once processing is complete, enter a query in the provided text box to retrieve answers from the processed data.
