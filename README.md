# LangChain Demo with LLAMA2 API

This project is a simple and clean demo application built with **Streamlit** and **LangChain**, integrating the **LLAMA2** language model via **Ollama**. It allows users to interact with a chatbot that responds intelligently to user queries.

## ✨ Features

- 🔥 Streamlit-based user interface
- �� Integration with LLAMA2 model using Ollama
- 🧠 Dynamic prompt engineering with LangChain
- 🔑 Environment variable management via `.env` (for API keys and settings)
- 🚀 Simple and lightweight architecture

## 📂 Project Structure

- **`localama.py`**: Main application file.
- **`.env`**: Store your LangChain API key securely.

## 🛠️ Installation

1. Clone the repository:

   ```bash
   https://github.com/ManmohanBora/Chatbot-Langchain-Ollama.git
   ```

2. Create a virtual environment and activate it:

   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/Mac
   venv\Scripts\activate     # For Windows
   ```

3. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Create a `.env` file in the root directory and add your LangChain API key:

   ```
   LANGCHAIN_API_KEY=your_langchain_api_key_here
   ```

## 🚀 How to Run

Run the Streamlit app:

```bash
streamlit run localama.py
```

## 🧹 Dependencies

- `streamlit`
- `langchain`
- `langchain-openai`
- `langchain-community`
- `python-dotenv`
- `ollama`

> You can generate the `requirements.txt` easily using:
>
> ```bash
> pip freeze > requirements.txt
> ```

## 📋 Notes

- Ensure that you have access to the **Ollama** service and that the **LLAMA2** model is available.
- Make sure your API keys are kept secure and never pushed to public repositories.

## 💬 Acknowledgments

- [LangChain](https://github.com/langchain-ai/langchain)
- [Ollama](https://ollama.com/)
- [Streamlit](https://streamlit.io/)

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

# requirements.txt

```
streamlit
langchain
langchain-openai
langchain-community
python-dotenv
ollama
```

