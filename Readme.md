# LangGraph AI Workflow with Langchain and Groq

## Overview

This project implements an AI-driven workflow using LangGraph, Langchain, and Groq's LLM. The system processes user queries, generates AI responses, and converts the responses to uppercase using a structured graph-based workflow.

## Features

**AI-Powered Response Generation:** Uses Groq's Llama3-70B model for intelligent text processing.

**State-Based Workflow:** Implements a LangGraph state graph to manage query processing.

**Automated Text Processing:** Converts AI responses to uppercase for emphasis.

**Graph Visualization:** Displays the workflow structure for better understanding.

## Installation

**Prerequisites**
Python 3.8+

Groq API Key

Setup

**Clone the repository:**

    git clone <repository_url>
    cd <repository_directory>

**Install the required dependencies:**

    pip install langgraph langchain langchain_community langchainhub ipykernel langchain-groq IPython

**Set up your API key:**

    If using Google Colab:

    from google.colab import userdata
    api_key = userdata.get('GROQ_API_KEY')

Otherwise, manually set it in the script:

    api_key = "your_groq_api_key"

**Run the script:**

    python main.py

## Usage

Run the script and provide an input query.

The system processes the query using Groq's LLM.

The response is converted to uppercase.

The final output is displayed.

## Code Structure

main.py: Main application file containing the workflow logic.

.env: Environment variables file for API keys.

requirements.txt: List of required Python packages.

## Dependencies

LangGraph: For managing AI-driven workflows.

LangChain: For integrating with Groq's LLM.

Google Colab: For API key storage (if applicable).

IPython: For displaying visual workflow representations.