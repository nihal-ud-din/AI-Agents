# 🍕 Pizza Restaurant AI Agent


An AI-powered assistant that answers questions about a pizza restaurant by retrieving relevant customer reviews and combining them with the power of LLaMA 3 via Ollama and LangChain. This project is a simple example of Retrieval-Augmented Generation (RAG) in action.


# 🧠 What It Does

Ask any question related to the restaurant—like:

* "Do they have vegan options?"
* "How's the ambiance?"
* "Is it family-friendly?" <br>
The AI agent fetches relevant reviews from a local vector database and generates an intelligent, context-aware response.

# 🛠 Tech Stack

* LangChain for LLM chaining and prompt templating 
* Ollama for running LLaMA 3 locally
* Vector-based retriever for semantic review search
* Python (no web interface yet—runs in terminal)

# 🌟 Why This Matters

This is a beginner-friendly example of how to build intelligent agents using open-source LLMs. It’s lightweight but powerful, and can be extended to any domain—ecommerce, healthcare, education, etc.

# 📂 File Structure

├── main.py               # Main script to run the AI agent
├── vector.py            # Contains the retriever logic
├── requirements.txt     # Dependencies
└── README.md            # You are here :)

