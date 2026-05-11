# LLM Chatbot Web App

LLM Chatbot Web App | Python, LangChain, Streamlit, OpenAI / LLaMA2

## Overview

Built an interactive LLM-powered chatbot web application using Streamlit and LangChain, supporting both cloud-based and local inference. The system integrates the OpenAI API for cloud responses and Ollama running LLaMA 2, enabling seamless switching between them based on requirement and flexible deployment across different environments.

The application uses LangChain’s ChatPromptTemplate for structured prompt design and StrOutputParser for consistent response formatting. The architecture allows switching between OpenAI and local models without modifying core logic.

## Features

- Dual LLM support: OpenAI API and local LLaMA2 via Ollama  
- Seamless switching between cloud and local models based on requirement  
- Interactive web interface using Streamlit  
- Structured prompt engineering using LangChain  
- Clean and consistent response formatting using StrOutputParser  
- Flexible and lightweight deployment design  

## Tech Stack

- Python  
- Streamlit  
- LangChain  
- OpenAI API  
- Ollama (LLaMA2)  

## How It Works

1. User enters a query in the Streamlit interface  
2. LangChain processes the input using a structured prompt  
3. Based on configuration, request is routed to:
   - OpenAI API (cloud) OR  
   - Local LLaMA2 via Ollama  
4. Response is formatted using StrOutputParser  
5. Output is displayed in the UI  

## Installation

git clone https://github.com/kriti524/LLM-Chatbot  
cd your-repo  
pip install -r requirements.txt  

## Run the Application

Start Ollama (for local model):

ollama run llama2  

Run Streamlit app:

streamlit run main.py  

## Environment Variables

Create a `.env` file:

LANGCHAIN_API_KEY=your_api_key_here  

## Impact

This project demonstrates the design of flexible LLM applications that work across both cloud and offline environments, addressing cost, privacy, and latency considerations while maintaining a smooth user experience.
