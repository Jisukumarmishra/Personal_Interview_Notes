# Embedding:--> Numerical representation of data meaning

# Zero-shot Prompt without examples

# Few-shot Prompt with a few examples

# vector search Finds semantically similar information

# Chunking Dividing documents into smaller sections

# Vector database Stores and searches embeddings

Function calling AI requests an external function/API with structured arguments
PII Personally Identifiable Information
Human-in-the-loop Human reviews or approves AI decisions
Explainability Understanding why AI produced a result
Auditability Ability to investigate past AI actions using records
Robustness Reliability under unexpected or adversarial inputs

# RAG Pipeline — Remember the Order

Documents → Chunking → Embeddings → Vector Database → Query Embedding → Retrieval → LLM → Answer

- RAG: Uses external information without retraining the model every time.
- Fine-tuning: Further trains a pretrained model.
- Semantic search: Searches by meaning, not just exact keywords.
- Overlap in chunks: Helps preserve context between sections.
