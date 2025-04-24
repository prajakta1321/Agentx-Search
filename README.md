# Agentx-Search
## LangChain × Tavily: Web Search and Answer Generation Agent
- This project demonstrates how to build an intelligent agent that performs web search and generates a natural language summary using LangChain and Tavily API, along with an LLM (OpenAI GPT). 

- It simulates how AI can be used to automate research and content drafting tasks with real-time information.

# 🔧 Technologies Used
🧩 LangChain – for orchestrating agent logic

🌐 Tavily API – to perform live web search queries

🤖 OpenAI API (GPT-3.5/4) – for summarizing search results

🐍 Python – all code is written in Python

📓 Google Colab – for interactive notebook execution

# ⚙️ How It Works
1. Search Agent

2. Takes a query from the user

3. Uses Tavily API to get real-time relevant results

4. Summarization Agent

5. Passes search results to a LLM

6. Generates a cohesive answer or summary

7. LangGraph Integration (Optional Extension)

8. Structure the workflow in a graph-like manner for clarity and modularity

9. Useful when combining multiple tools/agents

# 🧪 Sample Use Case
Query: *“How does LangChain help in building AI agents?”*

✔ Tavily fetches 2–3 relevant articles

✔ OpenAI summarizes those results into a concise paragraph

The final output is a ready-to-use draft for learning, research, or content writing

# ⚠️ Known Limitations
OpenAI API returned a rate limit (429) error due to exhausted quota

📝 The code logic and structure are present; execution is commented out or noted for evaluation

# 🗝️ Setup Instructions
Clone the notebook in Google Colab

Create and set your API keys:

✔ Tavily: https://app.tavily.com/

✔ OpenAI: https://platform.openai.com/account/api-keys

Install dependencies via:

- bash

- Copy

- Edit

- pip install langchain tavily-python openai

- Run each code cell step by step

# 🧠 Learnings and Contributions
✔ Explored prompt chaining using LangChain

✔ Integrated two separate AI APIs into one pipeline

✔ Learned about error handling (API keys, rate limits)

✔ Understood how agents can collaborate using tools like LangGraph

