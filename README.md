# 1ms25is048_assignment2
ReAct AI Agent using Gemini and document search
# ReAct Agent Using Gemini API

## Overview
This project implements a ReAct (Reason + Act) AI agent using Google's Gemini API and a custom document search tool. The agent processes user queries, retrieves relevant information from a predefined document collection, and generates responses based on the available information.

## Objective
To understand and implement the ReAct approach, enabling an AI model to interact with external tools, retrieve information, and generate context-aware responses.

## Technologies Used
- Python
- Google Gemini API
- Google Colab
- Google GenAI SDK

## Key Features
- Gemini-powered AI agent
- Custom document search functionality
- Function calling and tool integration
- ReAct reasoning and action loop
- Multiple query testing
- Source-based response generation

## How It Works
1. The user submits a question.
2. Gemini determines whether document search is required.
3. The agent calls the `search_documents` function.
4. Relevant documents are retrieved and returned to the model.
5. Gemini generates a final response using the retrieved information.

## Document Collection
The project uses five predefined documents covering:
- Artificial Intelligence
- Renewable Energy
- Space Exploration
- Cybersecurity
- Python Programming

## Project Structure
```text
ReAct-Agent-Assignment-2/
│
├── ReAct_Agent_1ms25is048_Assignment2.ipynb
└── README.md
```

## Setup and Execution
1. Open the Jupyter Notebook in Google Colab.
2. Install the required Python dependencies.
3. Generate a Gemini API key through Google AI Studio.
4. Configure the API key using Google Colab Secrets with the name `GOOGLE_API_KEY`.
5. Execute the notebook cells in sequence.
6. Test the agent using different questions.

## Expected Outcome
The agent should retrieve relevant documents for supported queries and generate responses based on the available information. If the documents do not contain the requested information, it should clearly indicate that the information is unavailable.

## Note
The Gemini API key is stored securely using Google Colab Secrets and is not included in this repository.

---

**Assignment:** Skill Lab – Assignment 2  
**Topic:** Deploy a ReAct Agent Using a Search Tool
