# Large Language Model Deployment with Llama's API and Streamlit

This project demonstrates how to deploy a large language model using Llama's API key and Streamlit, a popular Python library for creating interactive web applications.

## Introduction

This project provides a simple interface to interact with a large language model via Llama's API. Streamlit is used to create a user-friendly web application that allows users to input text and receive generated responses from the language model.

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/llama-streamlit-deployment.git
   cd llama-streamlit-deployment
   ```

2. **Create and activate a virtual environment**

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install the required packages**

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Set up your environment variables**

   Create a `.env` file in the root directory of the project and add your Llama API key:

   ```env
   LLAMA_API_KEY=your_llama_api_key_here
   ```

2. **Run the Streamlit application**

   ```bash
   streamlit run app.py
   ```

3. **Open your web browser**

   Go to `http://localhost:8501` to interact with the application.

## Configuration

- **API Key:** The Llama API key is required to authenticate and access the language model. Set this key in your `.env` file.
- **Port:** By default, Streamlit runs on port 8501. You can change this by modifying the run command:

  ```bash
  streamlit run app.py --server.port <your_port>
  ```
