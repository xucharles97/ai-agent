
# AI Agent

### Disclaimer

This is an AI chatbot interface created as a way to familiarize myself with AI development standards and protocols. Because it was created for educational purposes, all of the code was written manually without the use of generative AI.

## Design Overview
The AI functionality uses **GPT-5.4** via **OpenAPI** to implement a **Retrieval-Agumented Generation (RAG)** pipeline, which was coupled with **LangChain** components to enable semantic document comprehension and context-aware responses. This allows the user to upload a PDF through the frontend to be processed in the LLM's context.

A **MCP (Model Context Protocol)** server was used to combine the RAG outputs with the web search capabilities of Google's **SerpAPI**, resulting in a hybrid search strategy.

## Tech Stack

The key components of the tech stack are:

- **Express.js** and **Node.js** for backend development
- **LangChain** to integrate RAG functionality
- **GPT-5.4** via **OpenAPI**
- **SerpAPI** for web search functionality
- **React.js** for frontend development
- React's **speech-recognition** and **speak-tts** libraries for voice recognition functionality

## Backend

Backend development was conducted using **Express.js** and **Node.js**. The code for the backend can be found in the `/server` directory.

## Frontend

The frontend was written using **React.js**, leveraging the **antd** library for UI design and the **speech-recognition** and **speak-tts** libraries for voice recognition functionality. The frontend code can be found in the `/src` directory at the root of the repository.
