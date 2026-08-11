# 🤖 AI LLM Chatbot — Prompt Engineering & OpenAI API Integration

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![OpenAI](https://img.shields.io/badge/OpenAI-API_Integration-412991.svg?style=flat&logo=openai&logoColor=white)](https://platform.openai.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A lightweight, customizable **AI Chatbot** application leveraging the **OpenAI API** and modern **Prompt Engineering** techniques. This project demonstrates conversational AI integration, structured system prompting, and contextual response generation.

---

## 🌟 Key Features

- **OpenAI API Integration**: Real-time communication with LLM completion and chat endpoints.
- **System Prompt Engineering**: Customized persona definitions and output formatting rules.
- **Context Handling**: Basic conversation memory and token management.
- **Modular Code Architecture**: Clean separation between API caller, prompt template, and CLI interface.
- **Future Roadmap**: Designed to easily extend into Retrieval-Augmented Generation (RAG) for document Q&A.

---

## 🛠️ Tech Stack

- **Core Language**: Python 3.10+
- **LLM Provider**: OpenAI API (`gpt-3.5-turbo` / `gpt-4`)
- **Libraries**: `requests`, `python-dotenv`, `openai`

---

## 🚀 Quickstart & Installation

```bash
# 1. Clone the repository
git clone https://github.com/JaiswalKritika/ai-llm-chatbot.git
cd ai-llm-chatbot

# 2. Install dependencies
pip install -r requirements.txt

# 3. Set up environment variables
# Create a .env file and add your OpenAI API Key:
OPENAI_API_KEY=your_openai_api_key_here

# 4. Run the chatbot
python main.py
```

---

## 📂 Project Structure

```
ai-llm-chatbot/
├── main.py              # Application entry point
├── config.py            # API configuration and environment settings
├── prompts/             # System prompt templates
│   └── system_prompt.txt
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

---

## 🔮 Future Enhancements

- Integrate Vector Database (ChromaDB / Qdrant) for document-based RAG querying.
- Add Streamlit web user interface.
- Support open-source local LLMs via Ollama / HuggingFace.

---

## 👤 Author

**Kritika Jaiswal**  
- GitHub: [@JaiswalKritika](https://github.com/JaiswalKritika)  
- LinkedIn: [Kritika Jaiswal](https://www.linkedin.com/in/kritika-jaiswal-1405)
