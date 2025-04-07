# Local RAG Pipeline with HuggingFace Embeddings (Python 3.12)

This notebook demonstrates how to:

- Read local `.txt` and `.pdf` files `read_local_files.ipynb`
  - This is good enough for 'playing' but production would need many more examples of files AND longer files.
  - A single service would not be enough
- Chunk text for embedding
- Generate embeddings using a local HuggingFace model
- Save and load vector index locally
- Perform cosine similarity search without any external services
