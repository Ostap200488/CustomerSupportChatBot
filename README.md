# Customer Support ChatBot

An AI-powered customer support chatbot designed to answer user queries in real-time using modern LLM technologies and retrieval-based approaches.

This project demonstrates how to build an intelligent assistant capable of understanding user questions and providing accurate, context-aware responses.

---

##  Features

- 🤖 AI-powered conversational chatbot
- ⚡ Real-time responses
- 🧠 Context-aware answers using LLMs
- 📄 Custom knowledge base support
- 🔍 Retrieval-Augmented Generation (RAG) approach
- 💬 Clean and interactive chat interface

---

##  How It Works

The chatbot follows a modern AI pipeline:

1. User sends a question  
2. Text is processed and converted into embeddings  
3. Relevant information is retrieved from the knowledge base  
4. LLM generates a contextual response  
5. Answer is returned to the user  


##  Tech Stack

- Python
- LangChain
- OpenAI / LLM APIs
- Vector Database (Pinecone / ChromaDB)
- Flask / Streamlit (depending on your implementation)
- Embeddings & Semantic Search


##  Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Ostap200488/CustomerSupportChatBot.git
cd CustomerSupportChatBot

Create virtual environment
conda create -n chatbot python=3.10 -y
conda activate chatbot

Install dependencies
pip install -r requirements.txt
Create .env file
Add your API keys:
OPENAI_API_KEY="your_openai_key"
PINECONE_API_KEY="your_pinecone_key"
Run the application
python app.py
OR (if Streamlit is used):
streamlit run app.py
Open in browser
http://localhost:5000
OR (Streamlit):
http://localhost:8501

Author
Ostap Demchuk
Junior Software Developer
GitHub: https://github.com/Ostap200488
Portfolio: https://portfolio21345.netlify.app
