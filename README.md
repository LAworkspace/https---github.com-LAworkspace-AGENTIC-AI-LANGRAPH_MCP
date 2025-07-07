# Chatbot AI Agent

## Overview

Chatbot AI Agent is a Python-based project designed to create intelligent chatbot systems using advanced AI frameworks such as LangChain, LangGraph, and LangSmith. This project enables the development of conversational agents capable of understanding and responding to user queries effectively.

## Features

- **Interactive Chatbot**: Build and deploy chatbots with ease.
- **Tool Integration**: Leverage tools like TavilySearch and human assistance for enhanced functionality.
- **Graph-Based Workflow**: Utilize LangGraph for stateful and conditional workflows.
- **Environment Configuration**: Manage API keys and settings using `.env` files.

## Requirements

- Python >= 3.9
- Dependencies listed in `pyproject.toml`:
  - `ipykernel>=6.29.5`
  - `langchain>=0.3.26`
  - `langchain-community>=0.3.27`
  - `langchain-groq>=0.3.2`
  - `langchain-tavily>=0.2.4`
  - `langgraph>=0.4.8`
  - `langgraph-cli[inmem]>=0.3.3`
  - `langsmith>=0.4.1`
  - `python-dotenv>=1.1.0`
  - `twilio>=9.6.4`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/chatbot-ai-agent.git
   cd chatbot-ai-agent