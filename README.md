<h1 align="center">
Microsoft GraphRAG Template
</h1>

This is a template project to get us started with [graphrag](https://github.com/microsoft/graphrag/tree/main)

[GraphRag Official Documentation](https://microsoft.github.io/graphrag/)

## 🔧 Features
- A template with `poetry` environment
- A test data 
- Jupyter Lab Notebooks
- A simple Streamlit app
- Using the pre-defined / prepared data

## 💻 Running Locally On your Machine

1. Clone the repository 📂

```bash
git clone https://github.com/AliZaiN-157/ChatApp-Langchain.git
```

2. Install dependencies with [Poetry](https://python-poetry.org/) and activate virtual environment🔨

```bash
poetry install
poetry shell
```

3. Configure Environment Variables

given `.env.example`, rename to `.env` and replace the desired key with your OpenAI Key and Model


4. Run the Jupyter Notebook server🚀

```bash

jupyter notebook
```
Explore the sampled notebooks with sample data

5. Run the Python 

```bash

python src/global_search.py

or 

python src/local_search.py
```

6. Run the Streamlit server🚀

```bash

streamlit run --server.runOnSave=true  src/app.py
```

## Configure Indexing

`python -m graphrag.index --init --root ./ragtest`