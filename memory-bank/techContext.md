# Technical Context

## Core Libraries

### Document Processing
- **docling**: >=2.33 (Primary document parsing library for PDF/DOCX to markdown conversion)
- **docling-core**: Core functionality for docling
- **markitdown**: Microsoft's document conversion library (alternative parser)
- **langchain-text-splitters**: Text chunking and splitting utilities
- **transformers**: Hugging Face transformers library
- **rapidfuzz**: Fast fuzzy string matching

### Language Models & Embeddings
- **langchain-openai**: Azure OpenAI integration for LLMs and embeddings
- **langchain-google-genai**: Google Gemini model integration
- **sentence-transformers**: Hugging Face embedding models (e.g., multilingual-e5-large)
- **FlagEmbedding**: Advanced embedding models (>=1.3.3)
- **peft**: Parameter-Efficient Fine-Tuning library

### Vector Databases
- **pymilvus**: Milvus vector database client with model extensions
- **pymilvus[model]**: Extended Milvus client with AI model capabilities
- **elasticsearch**: Elasticsearch vector search capabilities

### Evaluation Framework
- **ragas**: RAG evaluation metrics framework
- **pydantic**: Data validation and configuration models
- **nltk**: Natural language processing utilities

### Utilities
- **tqdm**: Progress bars for long-running operations
- **python-dotenv**: Environment variable management
- **numpy**: Numerical computations
- **scipy**: Statistical analysis functions (t-tests, significance testing)

## External Dependencies

### Cloud Services
- **Azure OpenAI**: LLM and embedding services (GPT-4o, GPT-3.5-turbo-16k, GPT-4o-mini, GPT-4.1-mini, text-embedding-ada-002)
- **Google AI**: Gemini models (gemini-2.0-flash, gemini-2.5-flash-preview-05-20, gemini-2.5-pro-preview-05-06)
- **OpenRouter**: Multi-model API access
- **Zilliz Cloud**: Managed Milvus vector database service

### Local Services
- **Milvus Lite**: Local vector database for development
- **Elasticsearch**: Local search and vector storage (requires Docker)

### Environment Variables
```
AZURE_LLM_ENDPOINT, AZURE_LLM_API_VERSION, AZURE_LLM_API_KEY
AZURE_EMBEDDING_ENDPOINT, AZURE_EMBEDDING_MODEL, AZURE_EMBEDDING_API_VERSION, AZURE_EMBEDDING_API_KEY
GOOGLE_API_KEY
OPENROUTER_API_KEY
```

## Python Requirements
- **Python**: >=3.8 (recommended 3.12)
- **Build System**: setuptools>=42, wheel
- **Package Manager**: uv (recommended) or pip

## Development Tools
- **black**: Code formatting (line-length: 88, target: py38)
- **isort**: Import sorting (black profile)
- **Docker**: Required for local Elasticsearch setup

## Development Scripts
- **eval_rag.py**: Main evaluation pipeline script with configuration support
- **t-test.py**: Statistical comparison tool for RAG configuration analysis
- **workflow.png**: Visual representation of the evaluation pipeline workflow
