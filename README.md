# LLM Comparison

This app allows users to enter a prompt which will then return different responses by 3 different LLMs (OpenAi, Anthropic, and Ollama (Deepseek). It also displays the ranking of each AI model based on their
response speed.

## Preview

<img width="1114" height="613" alt="image" src="https://github.com/user-attachments/assets/2853884a-817c-4045-b337-c4ab98c8ffcb" />

## Features

* Integration with multiple LLM providers:
* REST API endpoints for interacting with each LLM
* React-based user interface for comparing model responses side-by-side

## Prerequisites

* Java 17 or higher
* Maven 3.6 or higher
* Node.js and npm
* API keys for OpenAI and Anthropic
* Ollama installed locally

### Backend Setup

1. Clone the repository:

       git clone https://github.com/AliiSheiikh/LLM-Compare.git

2. Configure your API keys in `application.properties` or via environment variables:

       spring.ai.openai.api-key=your_openai_key  
       spring.ai.anthropic.api-key=your_anthropic_key  
       # Other configuration properties...

3. Build the Spring Boot application:

### Frontend Setup

1. Navigate to the React UI directory:

       cd Frontend

2. Install dependencies:

       npm install

3. Build the UI:

       npm run dev
