# 📝 Notion Chatbot

This project is a **Notion Chatbot** built using **LangChain**, **OpenAI**, **FAISS**, and **Streamlit**.  
It allows you to chat with your Notion content by converting it into vector embeddings and building a retrieval-based conversational agent.

---

## ✨ Features

* Convert Notion content into vectors using the **OpenAI embedding model**.  
* Store vectors in a **FAISS index** for fast similarity search.  
* Build a **Conversation Retrieval Chain** using LangChain, with custom prompts and memory.  
* Deploy an interactive **Streamlit chat app** with the latest chat features.  

---

## 📚 Quick Start (Local)

### 1️⃣ Create a virtual environment
```bash
python3 -m venv venv
source venv/bin/activate
````

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit app

```bash
streamlit run app.py
```

Open your browser at [http://localhost:8501](http://localhost:8501)

---

## ⚙️ Tech Stack

* Python 3.8+
* Streamlit
* LangChain
* OpenAI API
* FAISS

---

## 🤖 How it works

1. Extract content from Notion.
2. Convert content to vector embeddings using OpenAI.
3. Store embeddings in a FAISS index for fast retrieval.
4. Build a LangChain Conversation Retrieval Chain with memory and custom prompts.
5. Users can ask questions in Streamlit, and the chatbot retrieves relevant content to answer.

---

## 🤝 Contributing

Contributions are welcome!
Please open an issue or submit a pull request for improvements or bug fixes.

---

## 📜 License

This project is licensed under the **MIT License**.
See the [LICENSE](./LICENSE) file for details.
