News Research Tool 📈

Overview
The News Research Tool is an AI-driven application designed to process and retrieve information from multiple news article URLs. Leveraging Streamlit, Langchain, FAISS, and OpenAI embeddings, this tool provides real-time question-answering capabilities along with source references. It is built to facilitate efficient information retrieval and analysis for research purposes.

Features
Data Extraction: Load news articles from URLs using UnstructuredURLLoader.
Text Segmentation: Split text into manageable chunks with RecursiveCharacterTextSplitter.
Embeddings Creation: Generate vector embeddings using OpenAIEmbeddings.
Efficient Retrieval: Store and retrieve data using a FAISS index.
Interactive Interface: User-friendly interface built with Streamlit for querying and displaying results.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/news-research-tool.git
cd news-research-tool
Create a virtual environment and activate it:

bash
Copy code
python3 -m venv venv
source venv/bin/activate
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Create a .env file and add your OpenAI API key:

makefile
Copy code
OPENAI_API_KEY=your_openai_api_key
Usage
Run the Streamlit app:

bash
Copy code
streamlit run main.py
Enter up to three news article URLs in the sidebar.

Click on the "Process URLs" button to start the data extraction and processing pipeline.

Once processing is complete, enter a query in the provided text box to retrieve answers from the processed data.
