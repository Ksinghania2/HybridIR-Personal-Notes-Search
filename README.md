# HybridIR-Personal-Notes-Search

Hybrid information retrieval for searching personal notes.

## Overview
This project implements hybrid search techniques combining keyword-based and semantic search for personal note retrieval. It helps you find information across your personal knowledge base.

## Features
- Hybrid search (keyword + semantic)
- Personal knowledge management
- Semantic search using embeddings
- Fast keyword retrieval
- Note organization and tagging

## Installation
```python
pip install -r requirements.txt
```

## Usage
```python
from hybridir import NoteSearcher
searcher = NoteSearcher()
searcher.add_note('title', 'content')
results = searcher.search('query')
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Topics
- hybrid-search
- information-retrieval
- personal-knowledge-management
- search
- semantic-search
```