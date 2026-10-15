Build your first LangGraph Agent

A small Math assisstant agent  to perform arithmetic operation.

What it can do:
- Understand questions like "What is 1200 divided by 4, minus 50 and multiplied by 20"
- Call real Python function (tools) to do arithmetic
- remembers earlier messages in the conversations
- Prints each step it takes so you can watch it think


Library:
- Python 3.14 or higher version
- LangGraph (graph engine + ready made helpers liek ToolNode)
- LangChain (init_chat_model to create chat model)
- Pytest
- langchain-google-genai (Google Gemini integration) or you can install any other LLM package
- python-dotenv (loads your API key from .env)


#### Clone the project
git clone https://github.com/abhaybharti/simple-langgraph-agent.git

#### Create a Virutal env
python3 -m venv .venv


#### Activate it
.venv\Scripts\Activate.ps1

#### Install the Dependencies
pip install -r requirements.txt

#### Run the Agent
python agent.py

#### Run tests
python -m pytest