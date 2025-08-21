# Basic-Chat-agent
# 🤖 Chatbot Agent using LangGraph & Groq LLM

This project is a **Chatbot Agent** built using **LangGraph**, **LangChain**, and **Groq-powered OpenAI OSS LLMs**.  
It demonstrates how to design a **graph-based conversational workflow** with state management and super-fast inference.  

---

## ⚙️ Tools & Frameworks Used
- 🐍 Python (Jupyter Notebook) → Development & testing  
- 🔗 LangChain → For prompt templates, chaining, and orchestration  
- 🧩 LangGraph → To design structured agent workflows with nodes & edges  
- ⚡ Groq LLM (openai/gpt-oss-20b) → Open-source large language model served at lightning speed  
- 📝 Prompt Engineering → To control chatbot behavior  
- 🎯 StrOutputParser → For clean model output parsing  

---

## 🛠️ How I Built This Project
1. Defined a **system prompt** to guide the chatbot’s role as a helpful assistant.  
2. Created a **prompt → LLM → parser pipeline** using LangChain.  
3. Added **state management** (`messages`) to maintain conversation history.  
4. Built a **LangGraph workflow**:  
5. Visualized the workflow using `mermaid` diagrams.  
6. Integrated Groq’s **OSS-20B model** for fast & cost-efficient responses.  

---

## 📌 Key Features
- ✅ Graph-based chatbot design with LangGraph  
- ✅ Maintains multi-turn conversation history  
- ✅ Uses Groq OSS LLMs for high-speed inference  
- ✅ Modular design – easy to extend with RAG, memory, or tools  
- ✅ Workflow visualization for better debugging  

---

## 🚀 Installation & Setup
Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/chatbot-agent.git
cd chatbot-agent
pip install -r requirements.txt
