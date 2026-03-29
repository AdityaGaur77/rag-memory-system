RAG Memory System
A Retrieval-Augmented Generation pipeline that improves AI memory accuracy.

Results
- Baseline LLaMA 3.2 (no RAG): 1/10
- RAG-enhanced LLaMA 3.2: 8/10
- When the temperature is set to 0: 7/20
- When k = 3: 8.6/10
- 80% improvement on long-context recall

To further tune performance, change the model's temperature and the k value.

Stack
Python, LangChain, ChromaDB, Ollama, LLaMA 3.2, SQuAD dataset
