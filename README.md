# LLM-Chatbot

LLM Chatbot Web App | Python, LangChain, Streamlit, OpenAI / LLaMA2

Built an interactive LLM-powered chatbot web application using Streamlit and LangChain, supporting both cloud-based and local inference.

The application integrates OpenAI API for cloud responses and Ollama with LLaMA 2 for offline usage, enabling flexible switching between hosted and local models.

Key LangChain components such as ChatPromptTemplate were used for structured prompt engineering, while StrOutputParser handled clean response formatting from the LLM outputs. The architecture allows seamless routing between OpenAI and local LLMs without changing the core application logic.

Key Highlights
Dual LLM support: OpenAI API and local LLaMA2 via Ollama
Built using LangChain prompt pipeline architecture
Interactive UI using Streamlit
Modular prompt engineering with ChatPromptTemplate
Clean output handling using StrOutputParser
Easy switching between local and cloud models
Impact

This project demonstrates the ability to design flexible LLM applications that work in both offline and cloud environments, making it suitable for real-world deployment scenarios where cost, privacy, and latency are important considerations.
