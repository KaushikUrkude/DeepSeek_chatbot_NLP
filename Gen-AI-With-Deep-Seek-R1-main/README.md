# DeepSeek-1.5B Chatbot with Streamlit & LangChain

This repository contains a chatbot implementation using **DeepSeek 1.5B**, **Streamlit**, and **LangChain**.

## Features
- Utilizes **DeepSeek 1.5B** for natural language processing
- Built using **LangChain** for structured conversations
- **Streamlit** for an interactive web-based UI

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Gen-AI-With-Deep-Seek-R1.git
cd Gen-AI-With-Deep-Seek-R1
```

### 2. Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```
Ensure `requirements.txt` includes:
```
streamlit
langchain_core
langchain_community
langchain_ollama
```

### 4. Download and Configure DeepSeek 1.5B Model
```bash
pip install deepseek
```

If using a local model:
```python
from deepseek import DeepSeek
model = DeepSeek("deepseek-ai/deepseek-coder-1.5b")
```


## Running the Chatbot
```bash
streamlit run app.py
```

## Usage
1. Open the provided Streamlit URL in your browser.
2. Enter a query in the chat input box.
3. The chatbot will generate responses using **DeepSeek 1.5B**.

## Project Structure
```
Gen-AI-With-Deep-Seek-R1/
│── app.py                # Main Streamlit app
│── requirements.txt      # Required dependencies
│── README.md             # Documentation
```

## Future Improvements
- Enhance response quality with prompt engineering.
- Implement memory for better conversational context.
- Deploy using **Docker** or **Hugging Face Spaces**.

## License
MIT License

---
Feel free to contribute and improve this project! 🚀

