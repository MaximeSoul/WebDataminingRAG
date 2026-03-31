# WebDataminingRAG




## Installation (Ollama needed)

Windows :
```bash
git clone https://github.com/MaximeSoul/WebDataminingRAG.git
cd WebDataminingRAG
python -m venv .venv
.\.venv\Scripts\activate
pip install -r requirements.txt
ollama run gemma3:4b
ollama list
```

Linux :
```bash
git clone https://github.com/MaximeSoul/WebDataminingRAG.git
cd WebDataminingRAG
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
ollama run gemma3:4b
ollama list
```

## Notebook explanation 

This project is divided in 4 labs.
- The First one is focus on data acquisition
- The Second one build the Knowledge Base (KB)
- The Third one compares the SWRL Reasoning with the Embedding
- The Fourth one is the core of the RAG

Each notebook can be run cell by cell. The first 3 of them will update the files in the data folder.
To test the RAG, the notebook must be run also and the question must be asked in the top bar.
There is no particular hardware requirement 