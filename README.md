# IK Agentic AI Course

This repository contains coursework and projects from the Interview Kickstart Agentic AI program, focusing on building intelligent AI agents using modern frameworks and techniques.

## 📚 Course Structure

### Week 1 - Fundamentals of Agentic AI
Introduction to core concepts and technologies in Agentic AI, including vector databases and Retrieval-Augmented Generation (RAG).

**Contents:**
- `Pinecone_Vector_db.ipynb` - Vector database implementation using Pinecone
- `RAG_Application.ipynb` - Retrieval-Augmented Generation application
- `dataset.txt` - Sample dataset for experiments
- `Fundamentals of Agentic AI - Assignment Solution.pdf` - Week 1 assignment solutions

**Key Topics:**
- Vector embeddings and similarity search
- Pinecone vector database setup and operations
- RAG architecture and implementation
- Document retrieval and generation workflows

### Week 2 - Build Your First Agent
Hands-on development of AI agents, including rule-based systems and LLM-powered chatbots.

**Contents:**
- `Build_Your_First_AI_Agent.ipynb` - Comprehensive guide to building AI agents

**Key Topics:**
- Rule-based chatbot implementation
- LLM-powered chatbots using Google's Gemini
- Medical RAG-based AI agent with web search
- Integration with Tavily search API
- ChromaDB for vector storage
- LangChain framework usage
- Conversation memory and context management

## 🛠️ Technologies Used

- **LLM Models:** Google Gemini (gemini-2.0-flash)
- **Vector Databases:** Pinecone, ChromaDB
- **Frameworks:** LangChain, LangGraph
- **APIs:** Google Generative AI, Tavily Search
- **Python Libraries:** 
  - `google-generativeai`
  - `langchain`
  - `langchain-google-genai`
  - `langchain_community`
  - `chromadb`
  - `pandas`

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Virtual environment (recommended)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/dceshubh/IK_Agentic_AI.git
cd IK_Agentic_AI
```

2. Create and activate virtual environment:
```bash
python -m venv ik_agentic_env
source ik_agentic_env/bin/activate  # On Windows: ik_agentic_env\Scripts\activate
```

3. Install dependencies:
```bash
pip install langchain google-generativeai langchain-google-genai langchain_community chromadb pandas
```

### API Keys Required

- **Google Gemini API:** [Get from Google AI Studio](https://aistudio.google.com/app/apikey)
- **Tavily Search API:** [Get from Tavily](https://tavily.com/)
- **Pinecone API:** [Get from Pinecone](https://www.pinecone.io/)

## 📖 Project Highlights

### Rule-Based Agent
A simple chatbot that responds based on predefined if-then rules, demonstrating basic agent logic without ML.

### LLM-Powered Chatbot
Conversational agent using Google's Gemini model with:
- Natural language understanding
- Context-aware responses
- Multi-turn conversations

### Medical RAG Agent
Advanced AI assistant for medical queries featuring:
- 256,916+ medical Q&A records
- Vector-based document retrieval
- Real-time web search integration
- Accurate, evidence-backed responses
- Context-aware multi-turn conversations

## 🎯 Learning Outcomes

- Understanding of agentic AI architecture
- Practical experience with vector databases
- Implementation of RAG systems
- Integration of LLMs with external tools
- Building production-ready AI agents
- Memory and context management
- Web search integration for real-time information

## 📝 Notes

- All notebooks are designed to run in Google Colab or local Jupyter environments
- API keys should be stored securely and never committed to version control
- The medical dataset contains real-world consultation data for educational purposes

## 🤝 Contributing

This is a personal learning repository. Feel free to fork and adapt for your own learning.

## 📄 License

Educational use only. Please respect the course materials and intellectual property.

## 👤 Author

Shubham Varshney
- Course: Interview Kickstart - Agentic AI Program

## 🔗 Resources

- [LangChain Documentation](https://python.langchain.com/)
- [Google AI Studio](https://aistudio.google.com/)
- [Pinecone Documentation](https://docs.pinecone.io/)
- [ChromaDB Documentation](https://docs.trychroma.com/)

---

*Last Updated: December 2024*
