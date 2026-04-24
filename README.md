# Text Splitters in LangChain 🦜🔗

A practical implementation of different Text Splitting techniques in LangChain including Length Based, Structure Based, Semantic Meaning Based, Markdown, and Python Code splitters.

---

## 📁 Project Structure
Text_Splitters_in_LangChain/
├── lengthbased_splitter.py
├── text_structure_based.py
├── semantic_meaning_based.py
├── markdown_splitting.py
└── python_code_splitting.py

---

## 🧠 Files Overview

| File | Description |
|---|---|
| `lengthbased_splitter.py` | Split text based on character or token length |
| `text_structure_based.py` | Split text based on structure using RecursiveCharacterTextSplitter |
| `semantic_meaning_based.py` | Split text based on semantic meaning using embeddings |
| `markdown_splitting.py` | Split Markdown files based on headers and structure |
| `python_code_splitting.py` | Split Python code based on functions and classes |

---

## 🔗 Text Splitters Explained

Long Text → Split by Length → Equal Size Chunks
### 2. Text Structure Based 🏗️
Splits text intelligently based on structure using RecursiveCharacterTextSplitter — most popular and widely used.
Long Text → Split by Structure → Meaningful Chunks
### 3. Semantic Meaning Based 🧠
Splits text based on semantic meaning using embeddings — most advanced splitting technique.
Long Text → Embeddings → Semantically Similar Chunks
### 4. Markdown Splitting 📝
Splits Markdown files based on headers and sections.
Markdown File → Split by Headers → Structured Chunks
### 5. Python Code Splitting 🐍
Splits Python code based on functions, classes, and logical blocks.
Python File → Split by Functions/Classes → Code Chunks
---

## 📊 Splitters Comparison

| Splitter | Best For | Difficulty |
|---|---|---|
| Length Based | Simple tasks | Easy |
| Structure Based | General use, RAG | Easy |
| Semantic Meaning | Advanced RAG | Medium |
| Markdown | Markdown files | Easy |
| Python Code | Code splitting | Easy |

---

## ⚙️ Setup & Installation

### 1. Clone the Repository
```bash
git clone https://github.com/waseemmalik82/Text_Splitters_in_LangChain.git
cd Text_Splitters_in_LangChain
```

### 2. Create Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate  # Windows
```

### 3. Install Dependencies
```bash
pip install langchain langchain-community langchain-text-splitters tiktoken
```

### 4. Setup API Keys
Create a `.env` file in the root folder:
OPENAI_API_KEY=your_openai_key
---

## 🚀 Usage

```bash
# Length Based Splitter
python lengthbased_splitter.py

# Text Structure Based Splitter
python text_structure_based.py

# Semantic Meaning Based Splitter
python semantic_meaning_based.py

# Markdown Splitter
python markdown_splitting.py

# Python Code Splitter
python python_code_splitting.py
```

---

## 🛡️ Important

- Never share your `.env` file
- `.env` is added to `.gitignore` for security
- Keep your API keys private at all times

---

## 👨‍💻 Author

**Waseem Malik**
GitHub: [@waseemmalik82](https://github.com/waseemmalik82)
### 1. Length Based Splitter 📏Long Text → Split by Length → Equal Size Chunks
Splits text based on character count or token count.
