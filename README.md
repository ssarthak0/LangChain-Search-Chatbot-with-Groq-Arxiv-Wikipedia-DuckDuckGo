# 🔎 LangChain Search Chatbot with Groq, Arxiv, Wikipedia & DuckDuckGo

This Streamlit application enables users to interact with a conversational AI agent that can search and retrieve information from multiple sources, including Arxiv, Wikipedia, and DuckDuckGo. It leverages LangChain's agent framework, Groq's LLMs, and Streamlit's interactive UI to provide real-time, context-aware responses.

---

## 🚀 Features

- **Multi-Source Search**: Integrates Arxiv, Wikipedia, and DuckDuckGo for comprehensive information retrieval.
- **Conversational Interface**: Maintains chat history for context-aware interactions.
- **Real-Time Feedback**: Utilizes `StreamlitCallbackHandler` to display the agent's thought process and actions.
- **Secure API Management**: Handles API keys securely via environment variables.

---

## 🛠️ Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/ssarthak0/LangChain-Search-Chatbot-with-Groq-Arxiv-Wikipedia-DuckDuckGo
   cd LangChain-Search-Chatbot-with-Groq-Arxiv-Wikipedia-DuckDuckGo
   ```

2. **Create and Activate a Virtual Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up Environment Variables**

   Create a `.env` file in the project root with the following content:

   ```env
   GROQ_API_KEY=your_groq_api_key
   ```

   Replace `your_groq_api_key` with your actual Groq API key.

---

## 📄 Usage

1. **Run the Application**

   ```bash
   streamlit run app.py
   ```

2. **Interact with the Chatbot**

   - Enter your Groq API key in the sidebar.
   - Type your query in the chat input box.
   - View the agent's thought process and responses in real-time.

---

## 📁 Project Structure

```
project-root/
├── app.py                 # Main Streamlit application
├── requirements.txt       # Python dependencies
├── .env                   # Environment variables
├── README.md              # Project documentation
```

---

## 🧾 Requirements

The application relies on the following Python packages:

```
langchain
python-dotenv
ipykernel
langchain-community
pypdf
bs4
langchain-text-splitters
langchain-openai
chromadb
sentence_transformers
langchain_huggingface
faiss-cpu
langchain_chroma
duckdb
pandas
openai
langchain-groq
duckduckgo-search
pymupdf
arxiv
wikipedia
huggingface_hub
```

Ensure all dependencies are installed by running:

```bash
pip install -r requirements.txt
```

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙏 Acknowledgments

- [LangChain](https://github.com/langchain-ai/langchain) for providing the framework for building LLM applications.
- [Streamlit](https://streamlit.io/) for the interactive web interface.
- [Groq](https://groq.com/) for the language models powering the chatbot.

---

